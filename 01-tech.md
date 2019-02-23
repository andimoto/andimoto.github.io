---
layout: default
title:  "Tech"
date:   2019-01-03 14:38:18 +0100
categories: tech
---
![pcb-macro](/img/pcb.jpg)
---
# Tech-Posts!
---
<br>

{% for category in site.categories %}
  <ul>
    {% if category[0] == "tech" %}
        {% for post in category[1] %}
            <li>{{ post.date | date: "%Y-%m-%d" }} :: <a href="{{ post.url }}">{{ post.title }}</a> </li>
        {% endfor %}
    {% endif %}
  </ul>
{% endfor %}


