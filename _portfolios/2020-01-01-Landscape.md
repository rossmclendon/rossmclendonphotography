---
title: 'Landscape'
subtitle: 'Beauty of the created and constructed'
date: 2018-06-30 00:00:00
description: Beauty of the created and constructed
featured_image: '/images/portfolio/landscape/ConimicutMoonrise_1500.jpg'
---

![]({{ site.baseurl }}/images/portfolio/landscape/OldStoneChurchPanorama_3000.jpg)

More of a personal passion, and largely how I developed my photogrpahy - I love to seek out and capture beautiful moments and scenes in the world around me.

Here are some examples of my landscape imagery.  Inquire about signed, limited prints on the [prints]({{ site.baseurl }}/prints) page.

<div class="gallery" data-columns="3">
{% for image in site.static_files %}
    {% if image.path contains 'images/portfolio/landscape' %}
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}
</div>