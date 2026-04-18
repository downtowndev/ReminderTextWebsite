---
layout: default
title: Blog
body_class: blog-index
full_width: true
permalink: /blog/
description: Product updates and SMS productivity guides from ReminderText.
---
<section class="section shell">
  <div class="section-heading reveal">
    <p class="section-kicker">ReminderText Blog</p>
    <h1>Product updates and SMS productivity ideas.</h1>
    <p>Simple strategies to help you build better reminder systems and keep routines on track.</p>
  </div>

  {% if site.posts.size > 0 %}
    <div class="post-grid reveal delay-1">
      {% for post in site.posts %}
        <article class="post-card">
          <p class="post-date">{{ post.date | date: "%B %-d, %Y" }}</p>
          <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
          <p>{{ post.excerpt | strip_html | truncate: 180 }}</p>
          <a class="text-link" href="{{ post.url | relative_url }}">Read post</a>
        </article>
      {% endfor %}
    </div>
  {% else %}
    <p>No blog posts yet. Check back soon.</p>
  {% endif %}
</section>
