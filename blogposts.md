---
layout: page
title: All Blog articles
---

<br><ul>{% for post in site.posts %}<li><h5> <a href="{{post.url}}">{{post.title}} <small>{{post.date | date_to_string}}</small> </a> </h5> </li>{% endfor %}</ul>
