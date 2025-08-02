---
layout: home
---

<div class="about-journal">

<h2>A Love Letter to Stories</h2>

<p>To the golden age of reportage.<br>
To the simple pleasure a good story.</p>

<p>This is a version of events.<br>
Cherished, missed, loud, quiet, fact, and fiction.</p>

<p>It's an outsiders perspective.<br>
An interpretation of the mundane.</p>

<p>It's a collection of connections. A public record of<br>
"This is who we were. This is what we did. This is why it mattered."</p>

</div>

<div class="wrapper">

<div class="posts-section">

<h2>Recent Posts</h2>

<div class="posts-grid">
  {% for post in site.posts limit:4 %}
  <div class="post-card">
    <a href="{{ post.url }}">
      <div class="post-image">
        {% if post.image %}
          <img src="{{ post.image }}" alt="{{ post.title }}">
        {% else %}
          <img src="/assets/images/the-crossing.jpg" alt="{{ post.title }}">
        {% endif %}
        <div class="post-overlay">
          <h3>{{ post.title }}</h3>
        </div>
      </div>
    </a>
  </div>
  {% endfor %}
</div>

<div class="view-more-container">
  <a href="/posts/" class="view-more-button">View More Posts</a>
</div>

</div> 