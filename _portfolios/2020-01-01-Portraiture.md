---
title: 'Portraiture'
subtitle: 'Beautiful images for your and your loved ones to cherish'
date: 2018-06-30 00:00:00
description: Beautiful images for your and your loved ones to cherish
featured_image: '/images/portfolio/portrait/KatieDress.jpg'
---

![](/images/portfolio/portrait/KatieDress.jpg)

From children to couples, headshots to families - I've got you covered.  

Here are some examples of my portraiture work.

<div class="gallery" data-columns="3">
{% for image in site.static_files %}
    {% if image.path contains 'images/portfolio/portrait' %}
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}
</div>