---
layout: archive
title: "SVG"
permalink: /svg/
author_profile: true
---

{% include base_path %}
{% capture written_label %}'None'{% endcapture %}

{% for collection in site.collections %}
  {% unless collection.output == false or collection.label == "posts" %}
