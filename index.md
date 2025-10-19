---
layout: home
title: Home
---

# Technical Blog

Welcome to my technical blog where I share insights on Red Hat technologies, infrastructure automation, and system administration.

## Recent Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## About

I'm a Red Hat Technical Account Manager (TAM) specializing in Ansible Automation Platform, RHEL, and enterprise infrastructure. This blog documents my journey through enterprise solutions and home lab experiments.

[View all posts →](/archive.html)
