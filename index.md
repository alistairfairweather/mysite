---
layout: page
title: Hi, I'm Alistair
---

I write stuff about technology. I'm also the founder of [PlainSpeak](https://www.plainspeak.co.za/), a consultancy focusing on the intersection between media, technology and business. 


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>