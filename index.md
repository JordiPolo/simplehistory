---
layout: default
title: Indice
---

**De Cero a Sapiens**

{% assign p = site.capitulos[0] %}
*  1.- [{{p.title}}]({% link /simplehistory/{{p.path | relative_url}} %}) ({{ p.dates }})
{% assign p = site.capitulos[1] %}
*  2.- [{{p.title}}]({{p.path | relative_url}}) ({{ p.dates }})
