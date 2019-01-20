---
layout: default
title:  "Photography"
date:   2019-01-02 19:33:18 +0100
categories: photography
---
![kiev88](/img/kiev88.jpg)
---
On this page you will find all posts about photography.

---
<br>
{% for category in site.categories %}
  <ul>
    {% if category[0] == "photography" %}
        {% for post in category[1] %}
            <li><a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
    {% endif %}
  </ul>
{% endfor %}
