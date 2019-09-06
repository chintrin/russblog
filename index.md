---
layout: default
title: Russ Chan
---

# Hi there, I'm Russ Chan!

Welcome to my blog.  This blog isn't career or technology specific, but rather
a place for me to collect various writings about all the stuff that I'm 
interested in.  

## Posts

<ul class="posts">
    {% for post in site.posts %}
    <li>
        <span>{{ post.date | date_to_string }}</span>
        »
        <a href="{{ site.baseurl }}{{ post.url }}"
           title="{{ post.title }}">
            {{ post.title }}
        </a>
    </li>
    {% endfor %}
</ul>
