---
layout: default
title: Prácticas de HTML de 1º Año
---


# Prácticas de HTML de 1º Año
Bienvenidos a página de prácticas de HTML de 1º Año

## Sección A

* [Nombres Apellid](pagina.html)

## Sección B

* [Nombres Apellid](pagina.html)

  {% for page in site.collections.legal.docs %}
* {{ page.url }} - {{ page.title }}
  {% endfor %}  <!-- page -->
