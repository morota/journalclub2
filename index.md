---
layout: page
title: RNA Biology Journal Club
tagline: 
---
{% include JB/setup %}

We discuss literature centered on RNA biology. Please subscribe to our RSS feed to follow if you are interested.  

### Posts [![](images/feed-icon-14x14.png)](rss.xml)

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

