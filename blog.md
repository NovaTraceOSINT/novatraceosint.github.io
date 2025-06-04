---
layout: default
title: Blog
---

# 📝 OSINT Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ https://novatraceosint.github.io/2025/06/03/msai-whatsapp-scam.html }}">{{ post.MSAI Scam }}</a> <small>({{ post.date | date: "06-03-25" }})</small>
    </li>
  {% endfor %}
</ul>
