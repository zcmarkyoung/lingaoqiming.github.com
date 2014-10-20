---
layout: page
title: 监高启明
tagline: Supporting tagline
---
{% include JB/setup %}

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

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.

穿越到乱世不是被雷劈，是他们自己的选择。
    
有人想称王制霸，有人想解民于倒悬，有人想以己之力，阻止最后一次野蛮对文明的征服，从而改写中华民族的历史。

当然也有人想得只是三妻四妾，过现世过不上的极度腐败的生活。
    
这群三心二意，各怀抱负的普通人，没有虎躯、没有王八之气更没有弱智光环道具。乱哄哄的挤在一艘旧船上，有的只是现代机器、科技还有各式各样的理论。穿越者们怀着现世无法达成的野心、梦想和理想，向着明末的乱世进发。

目标：海南。
