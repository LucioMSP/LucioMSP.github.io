---
layout: project
title: '.NET MAUI'
image: /assets/img/categories/maui-bot.png
screenshot: /assets/img/categories/maui-bot.png
caption: .NET, MAUI 
description: >
 La interfaz de usuario de la aplicación multiplataforma .NET (.NET MAUI) es un marco multiplataforma para crear aplicaciones nativas móviles y de escritorio con C # y XAML. Con .NET MAUI, puede desarrollar aplicaciones que pueden ejecutarse en Android, iOS, iPadOS, macOS y Windows desde una única base de código compartida.
---

{% assign posts = site.categories[page.slug] | default:site.tags[page.slug] | default:site.posts %}

{% if page.title.size > 0 %}
  <header>
   
  <hr class="sr-only"/>
{% endif %}


{% assign date_formats  = site.data.strings.date_formats               %}
{% assign list_group_by = date_formats.list_group_by | default:"%Y"    %}
{% assign list_entry    = date_formats.list_entry    | default:"%d %b" %}

{% for post in posts %}
  {% assign currentdate = post.date | date:list_group_by %}
  {% if currentdate != date %}
    {% unless forloop.first %}</ul>{% endunless %}
    <h2 id="{{ list_group_by | slugify }}-{{ currentdate | slugify }}" class="hr">{{ currentdate }}</h2>
    <ul class="related-posts">
    {% assign date = currentdate %}
  {% endif %}
  {% include components/post-list-item.html post=post format=list_entry %}
  {% if forloop.last %}</ul>{% endif %}
{% endfor %}