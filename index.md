---
layout: page
title: Dramanymity.net
tagline: a gallimaufry of monkeyshines
---
{% include JB/setup %}

Lorax ipsum gruvvulus thneed amet, snergelly once-ler lerkim, sed do
barbaloot tempor gluppitus ut labore et truffula magna aliqua.  Ut
enim ad grickle-grass veniam, quis miff-muffered ga-zumpco laboris
nisi ut cruffulus ex ea schloppity consequat.  Duis aute snarggle in
swomeeswans in voluptate axe-hacker esse rippulus crummii eu moof
nulla snuvv.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

Barbaloot tempor gluppitus ut labore et truffula magna aliqua.  Ut
enim ad grickle-grass veniam, quis miff-muffered ga-zumpco laboris
nisi ut cruffulus ex ea schloppity consequat.  Duis aute snarggle in
swomeeswans in voluptate axe-hacker esse rippulus crummii eu moof
nulla snuvv.
Lorax ipsum gruvvulus thneed amet, snergelly once-ler lerkim, sed do
barbaloot tempor gluppitus ut labore et truffula magna aliqua.  Ut
enim ad grickle-grass veniam, quis miff-muffered ga-zumpco laboris
nisi ut cruffulus ex ea schloppity consequat.  Duis aute snarggle in
swomeeswans in voluptate axe-hacker esse rippulus crummii eu moof
nulla snuvv.

<ul class="posts">
  {% for post in site.posts limit:10 %}
    <li><span class="posttitle">{{ post.date | date_to_string }} &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></span><p>{{ post.content | strip_html | truncatewords: 25 }}...</p></li>
  {% endfor %}

  <li><a href="/archive.html">Older posts</a></li>
</ul>

Ad grickle-grass veniam, quis miff-muffered ga-zumpco laboris
nisi ut cruffulus ex ea schloppity consequat.  Duis aute snarggle in
swomeeswans in voluptate axe-hacker esse rippulus crummii eu moof
nulla snuvv.
Lorax ipsum gruvvulus thneed amet, snergelly once-ler lerkim, sed do
barbaloot tempor gluppitus ut labore et truffula magna aliqua.  Ut
enim ad grickle-grass veniam, quis miff-muffered ga-zumpco laboris
nisi ut cruffulus ex ea schloppity consequat.  Duis aute snarggle in
swomeeswans in voluptate axe-hacker esse rippulus crummii eu moof
nulla snuvv.

<!--
Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Update Author Attributes

In `_config.yml` remember to specify your own data:

    title : My Blog =)

    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.

## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".
-->
