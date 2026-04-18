---
layout: default
title: ReminderText
body_class: home
full_width: true
permalink: /
description: ReminderText helps you schedule SMS reminders on iOS and Android, so important tasks never slip.
---
<section class="hero shell">
  <div class="hero-copy reveal">
    <p class="section-kicker">ReminderText for iOS and Android</p>
    <h1>SMS reminders that keep your day moving.</h1>
    <p class="hero-lede">ReminderText makes it easy to schedule and repeat text reminders for yourself, your family, or your team. Build dependable routines without opening a complicated productivity tool.</p>
    {% include download-buttons.html class='hero-downloads' %}
    <p class="hero-note">Free to download. Built for quick setup and reliable delivery.</p>
  </div>

  <figure class="hero-visual reveal delay-1">
    <img src="{{ '/assets/google-feature-graphic.png' | relative_url }}" alt="ReminderText app interface preview" width="1024" height="500">
  </figure>
</section>

<section id="features" class="section shell reveal">
  <div class="section-heading">
    <p class="section-kicker">Features</p>
    <h2>Built for real reminders, not busywork.</h2>
  </div>
  <div class="feature-grid">
    <article class="feature-card">
      <h3>Schedule in Seconds</h3>
      <p>Create a reminder quickly with a message, date, and recipient phone number.</p>
    </article>
    <article class="feature-card">
      <h3>Repeat With Confidence</h3>
      <p>Set recurring reminders for routines, recurring bills, medications, and work check-ins.</p>
    </article>
    <article class="feature-card">
      <h3>Status Visibility</h3>
      <p>Track whether reminders were scheduled and delivered so you stay in control.</p>
    </article>
  </div>
</section>

<section id="how-it-works" class="section shell reveal delay-1">
  <div class="section-heading">
    <p class="section-kicker">How It Works</p>
    <h2>Three simple steps.</h2>
  </div>
  <ol class="step-list">
    <li>
      <h3>Write your reminder</h3>
      <p>Type the text you want sent and choose who receives it.</p>
    </li>
    <li>
      <h3>Pick the timing</h3>
      <p>Set a one-time schedule or choose a repeating interval.</p>
    </li>
    <li>
      <h3>Let ReminderText handle delivery</h3>
      <p>The app handles scheduling and delivery attempts while you focus on your day.</p>
    </li>
  </ol>
</section>

<section class="section shell reveal">
  <div class="section-heading">
    <p class="section-kicker">App Preview</p>
    <h2>See ReminderText in action.</h2>
  </div>
  <div class="screenshot-grid">
    <figure class="screenshot-card tall">
      <img src="{{ '/assets/image2.jpeg' | relative_url }}" alt="ReminderText iOS screen showing reminder scheduling" width="1242" height="2688" loading="lazy">
    </figure>
    <figure class="screenshot-card tall">
      <img src="{{ '/assets/image3.jpeg' | relative_url }}" alt="ReminderText Android screen showing reminder details" width="1242" height="2688" loading="lazy">
    </figure>
    <figure class="screenshot-card wide">
      <img src="{{ '/assets/google-feature-graphic.png' | relative_url }}" alt="ReminderText feature graphic with app UI" width="1024" height="500" loading="lazy">
    </figure>
  </div>
</section>

<section id="faq" class="section shell reveal delay-1">
  <div class="section-heading">
    <p class="section-kicker">FAQ</p>
    <h2>Common questions.</h2>
  </div>
  <div class="faq-list">
    <details>
      <summary>Does ReminderText work on both iPhone and Android?</summary>
      <p>Yes. ReminderText is available on both iOS and Android with the same core scheduling experience.</p>
    </details>
    <details>
      <summary>Can I set recurring reminders?</summary>
      <p>Yes. You can create repeating reminders and manage them from your scheduled reminders list.</p>
    </details>
    <details>
      <summary>What if a reminder is not delivered?</summary>
      <p>Delivery is best-effort and can depend on carriers and network conditions. See the <a href="{{ '/undelivered-reminders' | relative_url }}">undelivered reminders policy</a> for details.</p>
    </details>
  </div>
</section>

<section class="section shell blog-teaser reveal">
  <div class="section-heading">
    <p class="section-kicker">From the Blog</p>
    <h2>SMS productivity tips and updates.</h2>
  </div>
  <div class="post-grid">
    {% for post in site.posts limit:2 %}
      <article class="post-card">
        <p class="post-date">{{ post.date | date: "%B %-d, %Y" }}</p>
        <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
        <p>{{ post.excerpt | strip_html | truncate: 150 }}</p>
      </article>
    {% endfor %}
  </div>
  <p><a class="text-link" href="{{ '/blog/' | relative_url }}">View all blog posts</a></p>
</section>
