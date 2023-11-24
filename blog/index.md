---
layout: default
---

# **Projects**

{% for post in site.posts %}

<div class="container">
    <div class="left">
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <p>{{post.description}}</p>
    </div>
    <div class="right">
        <img src="{{post.image}}">
    </div>
</div>

{% endfor %}