---
layout: page
title: Suen La
---
{% include JB/setup %}

<div class="signup">
  <h1><strong>suen·la<em>~</em></strong></h1>
  <p><strong>1.</strong> A Chinese phrase (算啦), meaning "forget about it."</p>
  <p><strong>2.</strong> A hilarious pun using my last name.</p>
  <p><strong>3.</strong> A weekly dispatch about creativity, culture, &amp; being a twentysomething—<strong>coming in August 2015.</strong></p>
  <!-- Begin MailChimp Signup Form -->
        <div id="mc_embed_signup">
        <form action="//whoismichaelsuen.us10.list-manage.com/subscribe/post?u=4ece89052ce51cd658a6e3155&amp;id=12c6ad1202" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
            <div id="mc_embed_signup_scroll">
          
        <div class="mc-field-group" style="display:inline-block;margin-right:8px">
          <input type="email" value="" placeholder="Your E-mail..." name="EMAIL" class="required email" id="mce-EMAIL">
        </div>
          <div id="mce-responses" class="clear">
            <div class="response" id="mce-error-response" style="display:none"></div>
            <div class="response" id="mce-success-response" style="display:none"></div>
          </div> <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
            <div style="position: absolute; left: -5000px;"><input type="text" name="b_4ece89052ce51cd658a6e3155_12c6ad1202" tabindex="-1" value=""></div>
            <div class="clear subscribe" style="display:inline-block"><input type="submit" value="Me Want!" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
            </div>
        </form>
        </div>
        <p class="note"><em>Sign up for articles that help you work &amp; play better, and think a little more about the way we live.</em></p>
    <!--End mc_embed_signup-->
</div>
<ul class="posts">
  {% for post in site.posts %}
    <li><strong>{{ post.date | date: "%B %-d" }}</strong> <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>