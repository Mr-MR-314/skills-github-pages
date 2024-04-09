---
title: Yaktocat Fan Page
layout: default  
---

# Welcome to the Yaktocat Fan Page!

## Yaktocat: The GitHub Icon

  *![Yaktocat Image](https://octodex.github.com/images/yaktocat.png)*

Yaktocat, the adorable black cat with a pull request and glowing red eyes, is the beloved official mascot of GitHub. Created by James Kang in 2011, Yaktocat represents the spirit of collaboration and open-source development.

## Fun Facts about Yaktocat

* Yaktocat is part of the GitHub Octodex, a collection of creative Octocat variations.
* You can find Yaktocat stickers, t-shirts, and other awesome merchandise.
* Yaktocat symbolizes the power of sharing and building amazing things together. 

## Let's Code Together!

Check out these blogs:
<div class="blog-list">
  {% for post in site.posts %}
    <h2><a href="https://mr-mr-314.github.io/skills-github-pages/{{ post.url }}">{{ post.title }}</a></h2>
    <p class="post-date">{{ post.date | date_to_string }}</p> 
  {% endfor %}
</div>

Inspired by Yaktocat? Start exploring the world of Git and GitHub! 
