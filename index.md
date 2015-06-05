---
title: Z\'s notes
layout: default
---
# {{ page.title }}
<zhouzhaoze@gmail.com>

## Useful links for Linux Users
* [Linux Shell Scripting Tutorial v1.05r3 A Beginner\'s handbook](http://www.freeos.com/guides/lsst/)
* [vbird linux](http://vbird.dic.ksu.edu.tw/)
* [POSIX Threads Programming](https://computing.llnl.gov/tutorials/pthreads/)


## My favoriate books
  * Introducation to Algorithms
  * Algorithms
  * C++ Primer

## 目录
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
