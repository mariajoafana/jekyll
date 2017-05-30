---
title: Índice de lecciones
layout: blank
permalink: /es/lecciones/
---

# Índice de lecciones

Nuestras lecciones están organizadas en fases típicas del proceso de investigación al igual que en temas generales. Uitliza los botones para filtrar las lecciones por categoría. Si no puedes encontrar la habilidad, tecnología o herramienta que estás buscando, por favor [déjanos saber]({{ site.baseurl }}/feedback)!

{% assign alllessons = (site.pages | where: "translated-lesson" , "true") %}

{% include lesson-index.html %}
