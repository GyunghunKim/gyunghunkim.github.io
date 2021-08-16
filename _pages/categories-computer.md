---
title: "Computer"
layout: archive
permalink: /computer
author_profile: false
sidebar:
    nav: "main"
---
{% assign posts = site.categories.computer %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}