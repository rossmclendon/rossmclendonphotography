---
title: 'Real Estate'
subtitle: 'Make your listing stand out from the crowd'
date: 2018-06-30 00:00:00
description: Make your listing stand out from the crowd
featured_image: '/images/portfolio/realestate/Exterior_1500.jpg'
---

![]({{ site.baseurl }}/images/portfolio/realestate/Exterior_1500.jpg)

In the age of smartphone snaps, quality images of your property can set your listing apart from the others.

Here are some examples of my real estate work.

<div class="gallery" data-columns="3">
{% for image in site.static_files %}
    {% if image.path contains 'images/portfolio/realestate' %}
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}
</div>