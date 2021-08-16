---
title: "Math"
layout: archive
permalink: /math
author_profile: false
sidebar:
    nav: "main"
---
{% assign posts = site.categories.math %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}