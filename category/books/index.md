---
layout: default
title: "Books"
category: books
permalink: /lab-notes/category/books/
---

{% for post in site.categories.books %}
  - [{{ post.title }}]({{ post.url }})
{% endfor %}
