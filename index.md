---
layout: post
title: technote
---

# <center> Technical Notes </center>

{% for post in paginator.posts %}
    - [post.title]("{{ post.url | prepend: site.baseurl }}")
    
{% endfor %}