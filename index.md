---
layout: splash
permalink: /
hidden: false
header:
  overlay_color: "#5e616c"
#   overlay_image: /assets/images/mm-home-page-feature.jpg
#   actions:
#     - label: "<i class='fas fa-download'></i> Install now"
#       url: "/docs/quick-start-guide/"
excerpt: >
  Ações desenvolvidas por discentes nas disciplinas Projeto Extensionista Integrado I, II e III, do curso de Engenharia Elétrica, do Centro Tecnológico da Universidade Federal do Espírito Santo.
#<br> <small><a href="https://ele.ufes.br/">Acesse para mais informações sobre as disciplinas.</a></small>

---
{% assign projetos_agrupados = site.projetos | group_by: "semestre" | sort: "name" | reverse %}

{% for grupo in projetos_agrupados %}
  <h2>Semestre {{ grupo.name }}</h2>

  <div class="projetos-list">
    {% for projeto in grupo.items %}
      <a href="{{ projeto.url | relative_url }}" class="card-projeto-minimal">
        <div class="card-content">
          <h3 class="card-title">{{ projeto.title }}</h3>
          <p class="card-excerpt">{{ projeto.excerpt }}</p>

          <div class="card-meta">
            {% if projeto.estudantes %}
              <span><i class="fas fa-user-graduate"></i> {{ projeto.estudantes | join: ", " }}</span>
            {% endif %}
            
            {% if projeto.semestre %}
              <span><i class="fas fa-calendar-alt"></i> {{ projeto.semestre }}</span>
            {% endif %}

            {% if projeto.parceiros %}
              <span><i class="fas fa-handshake"></i> {{ projeto.parceiros | join: ", " }}</span>
            {% endif %}
          </div>
        </div>

        {% if projeto.header.teaser %}
          <div class="card-image">
            <img src="{{ projeto.header.teaser | relative_url }}" alt="{{ projeto.title }}">
          </div>
        {% endif %}
      </a>
    {% endfor %}
  </div>
{% endfor %}