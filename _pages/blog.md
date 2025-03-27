---
layout: single
title: "Blog"
permalink: /blog/
author_profile: true
---

Here you can find my blog posts, which may include hand-written notes, code snippets, and personal reflections on research and ideas.

{% for post in site.blogs %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
