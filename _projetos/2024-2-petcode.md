---
title: "PETCODE (ProGramming e PetCode.ino)"
excerpt: 

layout: splash
author_profile: false
header:
  overlay_image: /assets/images/banner.jpg
  overlay_filter: 0.4
  show_overlay_excerpt: true
semestre: "2024.2"
publico_alvo: 
pessoas_beneficiadas: 
estudantes:
  - "Arthur Fiorio da Cunha" 
  - "Bernardo Canal Lacerda" 
  - "Kezia de Jesus de Souza" 
orientadores:
  - "Tiara Smarssaro de Freitas"
parceiros:
localidade: 
categories:
  - Computação
  - Eletrônica
tags:
  - Educação/Tutorial
  - Programação
materiais:
  github_repo: 
  youtube_channel: 
  youtube_channel_name: 
  youtube_playlist: "PLjzV9saqWJapuhqabfZgdYRXLHFsGE5y7"
  youtube_playlist_name: 
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

{% include materiais-projeto.html %}