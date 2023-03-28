---
layout: post
---

## Welcome to another page

_yay_
Text can be **bold**,

[맨위로](./)

{% for post in site.posts %}
<div class="card">
 <h3>{{post.title }}</h3>
  <p>Some Text</p>
<a href="{{post.url }}">{{post.title }}</a>
<br><br>
</div>
    {% endfor %}

    {% for javapost in site.javapost %}
<div class="card">
 <h3>{{javapost.title }}</h3>
  <p>Some Text</p>
<a href="{{javapost.url }}">{{javapost.title }}</a>
<br><br>
</div>
    {% endfor %}


