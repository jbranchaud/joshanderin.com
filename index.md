---
layout: default
title: Josh and Erin
---

<div id="posts">

    <ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url }}">
                {{ post.title }}
            </a>
        </li>
    {% endfor %}
    </ul>

</div>
