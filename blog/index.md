---
layout: default
---

# Projects

{% for post in site.posts %}

<ul>

<li><div class="container">
    <div class="left">
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <div class="right">
        <img src="{{post.image}}">
    </div>
</div></li>

<ul>

{% endfor %}