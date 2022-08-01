---
layout: archive
title: "Projects"
permalink: /
author_profile: true
---

A series of projects I have done over the past years. Including Machine Learning, Computer Vision, NLP, and robotics.

<br>
<br>

<div class="grid__wrapper">
    {% for post in site.posts %}
        {% if post.categories contains 'Projects' %}
            {% include archive-single.html type="grid" %}
        {% endif %}
    {% endfor %}
</div>
