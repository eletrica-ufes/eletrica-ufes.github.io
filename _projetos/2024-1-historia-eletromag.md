---
title: "História do Eletromagnetismo"
excerpt: "O projeto objetiva explicar conceitos complexos de eletromagnetismo de forma acessível e prática, abordando também o contexto histórico do desenvolvimento científico. Como resultado, foi criado um canal no YouTube com vídeos didáticos de experimentos concretos, demonstrando o funcionamento de uma bússola e de um motor elétrico caseiro e um vídeo sobre a história do eletrogmanetismo."
layout: splash
author_profile: false
header:
  overlay_image: /assets/images/banner.jpg
  overlay_filter: 0.4
  show_overlay_excerpt: true
  teaser: /assets/images/projetos/historia-eletromag/teaser.jpg
semestre: "2024.1"
publico_alvo: "Estudantes do ensino básico e o público geral com interesse em física, eletromagnetismo e ciência prática"
pessoas_beneficiadas: 
estudantes:
  - "Henrique Ferrario Traba"
  - "Ivan Grijó Farias"
  - "Larissa Barbosa Freitas"
  - "Roberto Antonio Pinto Hehr"
orientadores:
  - "Carlos Eduardo Schmidt Castellani"
parceiros:
localidade: 
categories:
  - "Eletromagnetismo"
tags:
  - "Divulgação Científica"
  - "Experimentos Didáticos"
materiais:
  github_repo: #usuario/repositorio
  website_url: 
  website_title: 
materiais:
  youtube_channel: "@HistoriadoEletromagnetismo"
  youtube_channel_name: "História do Eletromagnetismo"
gallery:
  # - url: /assets/images/projetos/ereds/IMG_8390.jpg
  #   image_path: /assets/images/projetos/ereds/IMG_8390.jpg
  #   alt: 
  #   title: haha
---


{% capture ficha_tecnica %}
##### <i class="fas fa-info-circle"></i> Ficha Técnica do Projeto
{% if page.publico_alvo %}
*  <i class="fas fa-users"></i>  **Público-Alvo:**  {{ page.publico_alvo }}
{% endif %}
{% if page.pessoas_beneficiadas %}
*  <i class="fas fa-heart"></i> **Pessoas beneficiadas:** {{ page.pessoas_beneficiadas }}
{% endif %}
{% if page.parceiros %}
*  <i class="fas fa-handshake"></i>  **Parceiros:**  {{ page.parceiros | join: ", " }}
{% endif %}
{% if page.localidade %}
*  <i class="fas fa-map-marker-alt"></i>  **Local:**  {{ page.localidade }}
{% endif %}
*  <i class="fas fa-user-graduate"></i>  **Discentes Responsáveis:**  {{ page.estudantes | join: ", " }}
*  <i class="fas fa-chalkboard-teacher"></i>  **Orientação:**  {{ page.orientadores | join: ", " }}
{% endcapture %}

<div class="notice--primary">
{{ ficha_tecnica | markdownify }}
</div>

## <i class="fas fa-bullseye"></i> Contexto
O ensino de conceitos de física e engenharia elétrica — especificamente os fenômenos associados ao eletromagnetismo — frequentemente esbarra na falta de ferramentas pedagógicas visuais e de metodologias ativas nas salas de aula convencionais. Sem demonstrações práticas e táteis, temas abstratos de eletricidade e magnetismo tornam-se de difícil compreensão para estudantes do ensino básico, gerando distanciamento de carreiras científicas e tecnológicas. 

Para suprir essa demanda e democratizar o conhecimento científico, o projeto estruturou estratégias de comunicação e educação voltadas ao ambiente digital de livre acesso. O foco consistiu em associar o desenvolvimento histórico das descobertas físicas à construção guiada de experimentos simples baseados em materiais comuns e de baixo custo, viabilizando a aprendizagem prática autônoma ou em laboratórios escolares.

## <i class="fas fa-tasks"></i> Atividades Realizadas
*   **Atividade 1: Criação e Gestão do Canal Digital:** Planejamento estratégico e lançamento do canal oficial do projeto no YouTube para compartilhamento público dos vídeos didáticos.
*   **Atividade 2: Produção de Vídeo Curto sobre Bússola Caseira:** Desenvolvimento de roteiro, roteirização e gravação de um experimento demonstrando o passo a passo para se fabricar uma bússola funcional utilizando materiais cotidianos como agulha magnetizada e uma superfície com água.
*   **Atividade 3: Produção de Vídeo Curto sobre Motor Homopolar:** Elaboração de experimento prático para gravação de vídeo demonstrando como criar um motor rotativo elétrico elementar empregando apenas uma pilha, um ímã e fio de cobre.
*   **Atividade 4: Elaboração do Vídeo Principal de Síntese Histórica:** Criação de um documentário em vídeo detalhando a evolução histórica do eletromagnetismo, cobrindo os experimentos pioneiros, descobertas fundamentais e as contribuições essenciais de cientistas clássicos como Michael Faraday, André-Marie Ampère e James Clerk Maxwell.

## <i class="fas fa-chart-line"></i> Resultados e Entregas

<div class="notice--success">
  <h4 style="margin-top:0;"><i class="fas fa-check-circle"></i> Principal Conquista</h4>
    <ul>
      <li>Criação de canal no Youtube com vídeos curtos de experimentos práticos e produção audiovisual aprofundada contextualizando a linha do tempo do eletromagnetismo e os impactos de suas descobertas científicas no avanço da tecnologia moderna.</li>
    </ul>
</div>


{% if page.materiais.pdf %}
  <div style="background: #f8f9fa; border: 1px solid #e1e4e8; border-radius: 8px; padding: 1.25rem; margin-bottom: 2rem; box-shadow: 0 2px 4px rgba(0,0,0,0.03);">
    <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 1rem; flex-wrap: wrap; gap: 0.5rem;">
      <h3 style="margin: 0; border: none; padding: 0;">
        <i class="fas fa-fw fa-file-pdf"></i> Documentação (PDF)
      </h3>
      <a href="{{ page.materiais.pdf | relative_url }}" class="btn btn--info" target="_blank" rel="noopener" style="margin: 0;">
        <i class="fas fa-fw fa-external-link-alt"></i> Abrir em nova aba
      </a>
    </div>
    <div style="border: 1px solid #e1e4e8; border-radius: 6px; overflow: hidden; background: #fff;">
      <iframe src="{{ page.materiais.pdf | relative_url }}" width="100%" height="500px" style="border: none; display: block;"></iframe>
    </div>
  </div>
{% endif %}

{% if page.materiais.github_repo %}
  <div style="background: #f8f9fa; border: 1px solid #e1e4e8; border-radius: 8px; padding: 1.25rem; margin-bottom: 2rem; box-shadow: 0 2px 4px rgba(0,0,0,0.03);">
    <div style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 0.75rem;">
      <div>
        <h3 style="margin: 0; border: none; padding: 0; font-size: 1.1em;">
          <i class="fab fa-fw fa-github"></i> {{ page.materiais.github_repo }}
        </h3>
        {% if page.github_desc %}
          <p style="margin: 0.3rem 0 0 0; font-size: 0.9em; color: #57606a;">
            {{ page.github_desc }}
          </p>
        {% endif %}
      </div>
      <a href="https://github.com/{{ page.materiais.github_repo }}" class="btn btn--primary" target="_blank" rel="noopener" style="margin: 0;">
        <i class="fas fa-fw fa-external-link-alt"></i> Ver no GitHub
      </a>
    </div>
  </div>
{% endif %}

{% if page.materiais.website_url %}
  <div style="background: #f8f9fa; border: 1px solid #e1e4e8; border-radius: 8px; padding: 1.25rem; margin-bottom: 2rem; box-shadow: 0 2px 4px rgba(0,0,0,0.03);">
    <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 0.75rem; flex-wrap: wrap; gap: 0.5rem;">
      <h3 style="margin: 0; border: none; padding: 0;">
        <i class="fas fa-fw fa-globe"></i> {{ page.website_title | default: "Plataforma Externa" }}
      </h3>
      <a href="{{ page.materiais.website_url }}" class="btn btn--primary" target="_blank" rel="noopener" style="margin: 0;">
        <i class="fas fa-fw fa-external-link-alt"></i> Acessar Site
      </a>
    </div>
  </div>
{% endif %}

{% if page.materiais.youtube_channel %}
  <div style="background: #f8f9fa; border: 1px solid #e1e4e8; border-radius: 8px; padding: 1.25rem; margin-bottom: 2rem; box-shadow: 0 2px 4px rgba(0,0,0,0.03);">
    <div style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 0.75rem;">
      <div>
        <h3 style="margin: 0; border: none; padding: 0; font-size: 1.1em;">
          <i class="fab fa-fw fa-youtube" style="color: #ff0000;"></i> {{ page.materiais.youtube_channel_name | default: "Canal do YouTube" }}
        </h3>
        <p style="margin: 0.3rem 0 0 0; font-size: 0.9em; color: #57606a;">
          Acesse para assistir aos vídeos e projetos no canal oficial.
        </p>
      </div>
      <a href="https://www.youtube.com/{{ page.materiais.youtube_channel }}" class="btn btn--danger" target="_blank" rel="noopener" style="margin: 0;">
        <i class="fas fa-fw fa-external-link-alt"></i> Visitar Canal
      </a>
    </div>
  </div>
{% endif %}

{% if page.gallery %}
  <div style="background: #f8f9fa; border: 1px solid #e1e4e8; border-radius: 8px; padding: 1.25rem; margin-bottom: 2rem; box-shadow: 0 2px 4px rgba(0,0,0,0.03);">
    <h3 style="margin-top: 0; margin-bottom: 1rem; border: none; padding: 0;">
      <i class="fas fa-fw fa-images"></i> Galeria de Fotos
    </h3>
    {% include gallery %}
  </div>
{% endif %}