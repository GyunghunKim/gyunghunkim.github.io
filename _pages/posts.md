---
title: "All Posts"
layout: archive
permalink: /posts
author_profile: false
sidebar:
    nav: "main"
---
{% assign posts = site.posts %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}