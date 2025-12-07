---
layout: default
title: Home
---

<section class="posts-list">
  <h2>Latest posts</h2>

  {% for post in site.posts %}
  <article class="post-item">
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <div class="post-meta">
      <time datetime="{{ post.date | date_to_xmlschema }}">
        {{ post.date | date: "%Y-%m-%d %H:%M %Z" }}
      </time>
      {% if post.author %} • <span class="author">{{ post.author }}</span>{% endif %}
    </div>

    <div class="post-excerpt">
      {{ post.excerpt | strip_html | truncate: 280 }}
    </div>

    <p><a href="{{ post.url | relative_url }}">Read more →</a></p>
  </article>
  <hr />
  {% endfor %}
</section>
