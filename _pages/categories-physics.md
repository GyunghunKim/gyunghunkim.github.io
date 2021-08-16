---
title: "Physics"
layout: archive
permalink: /physics
author_profile: false
sidebar:
    nav: "main"
---
{% assign posts = site.categories.physics %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}