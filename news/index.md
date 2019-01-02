---
layout: page
title: News
permalink: /news/
---



<link href="//cdn-images.mailchimp.com/embedcode/slim-081711.css" rel="stylesheet" type="text/css">
<div id="mc_embed_signup">
<form action="//github.us11.list-manage.com/subscribe/post?u=396763b695fc63ad2656f7683&amp;id=b32a934486" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
<div id="mc_embed_signup_scroll">
<label for="mce-EMAIL">Subscribe to receive the news by email</label>
<input type="email" value="" name="EMAIL" class="email" id="mce-EMAIL" placeholder="email address" required>
<!-- real people should not fill this in and expect good things - do not remove this or   risk form bot signups-->
<div style="position: absolute; left: -5000px;"><input type="text" name="   b_396763b695fc63ad2656f7683_b32a934486" tabindex="-1" value=""></div>
<div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button"></div>

<br>

<p>Subscribe to receive the news with <a href="{{ site.baseurl }}/feed.xml"><i class="fa fa-rss"></i> RSS</a></p>

<hr>

{% for post in site.posts %}

<h5><small>{{ post.date | date_to_string }}</small><br><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h5>

{% endfor %}

<br><br>





