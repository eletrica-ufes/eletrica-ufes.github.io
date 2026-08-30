---
title: "Desenvolvimento de conteúdo multimídia didático de uma linguagem de programação do nível básico até um nível intermediário."
excerpt: "Criação de trilha didática de Python (lógica básica, NumPy, Pandas e Tkinter), resultando na publicação de 58 videoaulas no canal 'Python Tutoriais UFES' no YouTube, disponibilização do código-fonte no GitHub e alcance de 65 inscritos no primeiro ciclo do projeto."

layout: splash
author_profile: false
header:
  overlay_image: /assets/images/banner.jpg
  overlay_filter: 0.4
  show_overlay_excerpt: true
semestre: "2024.1"
publico_alvo: "Estudantes de escolas públicas, comunidade acadêmica e entusiastas de programação."
pessoas_beneficiadas: 
estudantes:
  - "Eduardo Capobiango Ferraz"
  - "Gustavo Nunes Lopes"
  - "Mateus Biancardi da Silva"
  - "Yago de Souza Pereira"
orientadores:
  - "Patrick Marques Ciarelli"
parceiros:
localidade: 
categories:
  - Computação
  - Educação/Tutorial
tags:
  - Python
  - Lógica de Programação
  - Pandas
  - Tkinter
materiais:
  github_repo: "guxtaavo/PythonUFES"
  youtube_channel: "@PythonTutoriaisUFES"
  youtube_channel_name: "Python Tutoriais UFES"
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

## <i class="fas fa-bullseye"></i> Objetivos do Projeto

*   **Desenvolver conteúdo multimídia didático** voltado ao ensino de uma linguagem de programação (Python), cobrindo desde o nível básico até o nível intermediário.
*   **Adotar a metodologia ágil Kanban** para gerenciar as tarefas, permitindo uma visualização clara do progresso do curso e garantindo o engajamento contínuo dos participantes.

## <i class="fas fa-tasks"></i> Atividades Realizadas

*   **Atividade 1: Planejamento e Organização via Kanban:** Adoção da metodologia ágil Kanban para gerenciar cada uma das tarefas do projeto, garantindo uma visualização clara do progresso do desenvolvimento do curso e o engajamento contínuo dos participantes. Para a aplicação prática do Kanban, foi utilizada a plataforma de uso gratuito Taiga (https://tree.taiga.io/discover).
*   **Atividade 2: Preparação Didática do Conteúdo de Python:** Estruturação e desenvolvimento de roteiros e aulas cobrindo desde conceitos básicos de lógica de programação até o nível intermediário, capacitando os alunos a trabalharem com scripts e sintaxes funcionais.
*   **Atividade 3: Ensino de Bibliotecas de Ciência de Dados:** Preparação de conteúdo e gravação de videoaulas dedicadas ao uso prático de bibliotecas fundamentais de manipulação e visualização de dados, especificamente as bibliotecas **Pandas**, **NumPy** e **Matplotlib**.
*   **Atividade 4: Construção de Interface Gráfica Prática:** Desenvolvimento e programação de uma aplicação prática para consolidar o aprendizado, ensinando a criação e a estruturação de uma calculadora funcional para desktop utilizando a biblioteca de interface gráfica **Tkinter**.
*   **Atividade 5: Publicação e Campanha de Divulgação:** Gravação de videoaulas didáticas, publicação do material em formato assíncrono no YouTube e realização de uma campanha de divulgação para atrair a comunidade externa e expandir o número de visualizações do canal.


## <i class="fas fa-chart-line"></i> Resultados e Entregas

<div class="notice--success">
  <h4 style="margin-top:0;"><i class="fas fa-check-circle"></i> Principais Conquistas</h4>
    <ul>
      <li>Disponibilização de uma trilha de aulas didáticas sobre bibliotecas essenciais do Python, abordando Séries, DataFrames e manipulação de arquivos CSV/JSON com Pandas, além da integração com o Matplotlib para análise de dados.</li>
      <li>Criação e compilação do executável de uma calculadora desktop desenvolvida em Tkinter, servindo como projeto prático final para a construção de interfaces gráficas.</li>
      <li>Produção e edição integral do material multimídia utilizando exclusivamente ferramentas gratuitas, incluindo OBS Studio para gravação, CapCut para edição de vídeo e VS Code como ambiente de desenvolvimento.</li>
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