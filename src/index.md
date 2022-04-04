---
title: Hello Franz Blog
layout: "base.njk"
---

Hello jamstack fanz!

{% for post in collections.posts %}

- [{{ post.data.title }}]({{post.url}})
{% endfor %}