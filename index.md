---
layout: default
title: Indice
---

**De Cero a Sapiens**

{% assign p = site.capitulos[0] %}
*  1.- [{{p.title}}]({% link {{p.path}} %}) ({{ p.dates}})
{% assign p = site.capitulos[1] %}
*  2.- [{{p.title}}]({% link {{p.path}} %}) ({{ p.dates}})


{% comment %}
No idea why the below creates text and not code
{% assign count = 0 %}

**De Cero a Sapiens**

{% for post in site.capitulos %}
 {% assign count = count | plus: 1 %}
  {% if post.category == "cero" %}
    * 1.- [{{post.title}}]({% link {{ post.path| relative-url }} %}) {{ post.dates}}
  {% endif %}
{% endfor %}
{% endcomment %}
