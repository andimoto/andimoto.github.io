---
layout: default
title:  "Travel"
date:   2019-01-02 19:33:18 +0100
categories: travel
---

---
{% comment %}
{% include image.html url="../../../../img/travel.jpg" %}
{% endcomment %}
![travel-cat](/img/travel.jpg)
---
<br>
{% for category in site.categories %}
  <ul>
    {% if category[0] == "travel" %}
        {% for post in category[1] %}
            <li><a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
    {% endif %}
  </ul>
{% endfor %}
