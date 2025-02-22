---
layout: default
title: Home
---
### Life update

Hello my name is Jerry and I am writing short stories and Austin is watching over my shoulder whilst I edit this stuff like an octagenarian lol.

<img src="https://picsum.photos/200"/>


### Recent posts

<div class='gallery'>
  {% for post in site.posts %}
    <a style='color: black; text-decoration: none;' href='{{ post.url }}'>
      <img src='{{ post.image }}'>
      <p>{{ post.date | date_to_string }}: {{ post.title }}</p>
    </a>
    {% if forloop.index >= 3 %}
      {% break %}
    {% endif %}
  {% endfor %}
</div>
