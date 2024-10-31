---
layout: layouts/grid-news.njk
title: News about Club Events and Swim NSW Meets
description: 
section: news
class: news
date: 2024-10-29
permalink: /news/
metadata:
  title: Gloucester Thunderbolts Swimming Club Events and Swim NSW Meets
eleventyNavigation:
  key: News
  order: 3
---



### Interested in swimming?

**Cool, then some of this stuff may interest you too.**

{% for post in collections.news %}
<article class="news-item">
  <h2><a href="{{ post.url }}">{{ post.data.title }}</a></h2>
  <p>{{ post.data.date }}</p>
  <p>{{ post.data.eventdate.day }} {{ post.data.eventdate.month }} {{ post.data.eventdate.year }}</p>
  <p>{{ post.data.tags }}</p>
  <p>{{ post.data.time }}</p>
  <p>{{ post.data.where }}</p>
  <p>{{ post.data.map }}</p>
  <p>{{ post.data.articlelink }}</p>
  <p>{{ post.data.articlePDF }}</p>
  <p>{{ post.data.articlePDFtitle }}</p>
  <p>{{ post.data.articlePDF2 }}</p>
  <p>{{ post.data.articlePDFtitle2 }}</p>
  <p>{{ post.data.image }}</p>
  <p>{{ post.data.articlelink }}</p>
  <p>{{ post.data.articlePDF }}</p>
  <p>{{ post.data.articlePDFtitle }}</p>
  <p>{{ post.data.articlePDF2 }}</p>
  <p>{{ post.data.articlePDFtitle2 }}</p> 
  <p>{{ post.data.time }}</p>



</article>
{% endfor %}

```



