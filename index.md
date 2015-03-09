---
layout: page
title: Suen La
---
{% include JB/setup %}

<div class="signup">
  <h1><strong>suen·la</strong></h1>
  <p><strong>1.</strong> A Chinese phrase (算啦), meaning "forget about it."</p>
  <p><strong>2.</strong> A hilarious pun using my last name.</p>
  <p><strong>3.</strong> A multimedia column on creativity, culture, and being a twentysomething—<em><strong>coming soon.</strong></em></p>
</div>
<ul class="posts">
  {% for post in site.posts %}
    <li><strong>{{ post.date | date: "%B %-d" }}</strong> <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>