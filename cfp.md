---
layout: page
title: Call for Papers
---

This workshop will explore how artificial intelligence can contribute to solving social problems. For example, what role can AI play in promoting health, access to opportunity, and sustainable development? How can AI initiatives be deployed in an ethical, inclusive, and accountable manner? To address such questions, this workshop will bring together researchers and practitioners across artificial intelligence and a range of application domains. The objective is to share the current state of research and practice, explore directions for future work, and create opportunities for collaboration. The workshop will feature a mix of invited talks, contributed talks, and posters. Submissions spanning the full range of theoretical and applied work are encouraged. Topics of interest include, but are not limited to:

* Democracy
* Developing world
* Health
* Environmental sustainability
* Ethics
* Fairness and biases

Submissions are due <b> April 12</b>. The submission site will be posted closer to that date. 


<div class="posts">
  {% for post in paginator.posts %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div>

