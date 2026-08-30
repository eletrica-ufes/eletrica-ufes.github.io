---
title: 
excerpt: # Resumo do projeto

layout: splash
author_profile: false

# Banner Superior (Hero Image)
header:
  overlay_image: /assets/images/banner.jpg
  overlay_filter: 0.4 # Escurece a imagem para dar contraste ao título
  show_overlay_excerpt: false
  #teaser: /assets/images/projetos/<>/nome-do-arquivo.jpg

# Dados extensão
semestre: 
publico_alvo: 
pessoas_beneficiadas: 

# Equipe e Parcerias
estudantes:
  - 
orientadores:
  - 
parceiros:
  - 
localidade: 

# Categorização
categories:
  - # Área na engenharia elétrica
tags:
  - 
  - 
---
{% capture ficha_tecnica %}
### <i class="fas fa-info-circle"></i> Ficha Técnica do Projeto

* <i class="fas fa-users"></i> **Público-Alvo:** {{ page.publico_alvo }}
<!-- * <i class="fas fa-heart"></i> **Impacto Estimado:** {{ page.pessoas_beneficiadas }}+ pessoas beneficiadas -->
* <i class="fas fa-handshake"></i> **Parceiros:** {{ page.parceiros | join: ", " }}
* <i class="fas fa-map-marker-alt"></i> **Local:** {{ page.localidade }}
* <i class="fas fa-user-graduate"></i> **Discente Responsável:** {{ page.estudantes | join: ", " }}
* <i class="fas fa-chalkboard-teacher"></i> **Orientação:** {{ page.orientadores | join: ", " }}
{% endcapture %}

<div class="notice--primary">
  {{ ficha_tecnica | markdownify }}
</div>

## <i class="fas fa-bullseye"></i> Contexto e Demanda da Comunidade


---

## <i class="fas fa-tasks"></i> Atividades Realizadas

* **Atividade 1:** <inserir descrição da atividade>

---

## <i class="fas fa-chart-line"></i> Resultados e Entregas

<div class="notice--success">
  <h4 style="margin-top:0;"><i class="fas fa-check-circle"></i> Principais Conquistas</h4>
  <ul>
    <li><b></li>
  </ul>
</div>

---

<!-- ## <i class="fas fa-camera"></i> Registros de Campo e Mapeamento

<figure class="third">
  <a href="/assets/images/projetos/2026-1-fotovoltaica/terreno.jpg">
    <img src="/assets/images/projetos/2026-1-fotovoltaica/terreno.jpg" alt="Área do Terreno">
  </a>
  <a href="/assets/images/projetos/2026-1-fotovoltaica/fachada.jpg">
    <img src="/assets/images/projetos/2026-1-fotovoltaica/fachada.jpg" alt="Fachada do Instituto">
  </a>
  <a href="/assets/images/projetos/2026-1-fotovoltaica/satelite.jpg">
    <img src="/assets/images/projetos/2026-1-fotovoltaica/satelite.jpg" alt="Análise de Satélite">
  </a>
  <figcaption>Levantamento de campo, análise de fachadas e mapeamento aéreo via satélite.</figcaption>
</figure> -->