---
layout: default
title: Indice
---

**De Cero a Sapiens**

{% assign p = site.capitulos[0] %}
*  1.- [{{p.title}}]({{p.url | relative_url}}) ({{ p.dates }})
{% assign p = site.capitulos[1] %}
*  2.- [{{p.title}}]({{p.url | relative_url}}) ({{ p.dates }})
{% assign p = site.capitulos[2] %}
*  3.- [{{p.title}}]({{p.url | relative_url}}) ({{ p.dates }})
{% assign p = site.capitulos[3] %}
*  4.- [{{p.title}}]({{p.url | relative_url}}) ({{ p.dates }})

