---
layout: page
title: Home
subtitle: Ramblings of a Hypocritical Environmentalist Technophile
---
{% include JB/setup %}

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

# Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo;
       <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

# Ramblings of a Hypocritical Environmentalist Technophile

<p>Eventually this will become a blog for all kinds of topics, including UAVs,
Tech, Environment etc..</p>
## To-Do
* At the moment, this is the same theme as Richard's blog, which needs changing
, as I would like the colours to be different, however I somehow managed to
 break things when attempting to modify the theme...
