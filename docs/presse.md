---
layout: post
title: Presse
---

## Presseinformationen

* **Webseite**: [www.bleibtoffen.org](https://www.bleibtoffen.org)
* **Ansprechpartner**: Claas Augner – [bleibtoffen@caugner.de](mailto:bleibtoffen@caugner.de)

## Pressemitteilungen

* [1. Pressemitteilung vom 12.04.2020]({% post_url 2020-04-12-pressemitteilung %}) ([Deutsch]({% post_url 2020-04-12-pressemitteilung %}), [English]({% post_url 2020-04-12-press-release %}), [Français]({% post_url 2020-04-12-press-release %}))

## Medien

### Logo
{% for item in site.data.presse.logo %}
{% include presse.html %}
{% endfor %}

### Banner

{% for item in site.data.presse.banner %}
{% include presse.html %}
{% endfor %}

### Screenshots

{% for item in site.data.presse.screenshot %}
{% include presse.html %}
{% endfor %}