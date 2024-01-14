---
title: "HPSC Center at National Taiwan University - Publications"
layout: gridlay
excerpt: "HPSC Center at National Taiwan University -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## Group highlights

## Full List of publications
{% for publi in site.data.publist %}
  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% endfor %}