---
title: "linux"
layout: archive
permalink: /linux
author_profile: true
---


{% assign posts = site.categories.linux %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}