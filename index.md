---
layout: page
title: Michael Hagedorn
tagline: My Github Stuff
---
{% include JB/setup %}

My Companies

My Bio (of sorts) [Here](http://appsdynamic.com/about.html)

The Original [Silverchair Solutions](http://www.silverchairsolutions.com) 

The Newer One [Applied Software Dynamics](http://www.appsdynamic.com) 

Both are still valid


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




