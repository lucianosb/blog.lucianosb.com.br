---
layout: page
title: Bem-vindo(a)!
tagline: Este é meu blog
---
{% include JB/setup %}


## Posts Recentes

Eis meus textos mais recentes. Se preferir pode navegar por Categoria ou Assuntos (Tags) pelo menu acima.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
