---
title: "Allan Lab - Publications"
layout: gridlay
excerpt: "Allan Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## Conference

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

