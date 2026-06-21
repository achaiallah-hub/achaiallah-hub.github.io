---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

My academic research falls into two main areas


{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %} {% include archive-single.html type="grid" %} {% endfor %}