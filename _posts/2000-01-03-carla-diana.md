---
layout: default
---

<article class="post">
  <header style="margin-bottom: 18px;">
    <h1 style="margin-bottom: 8px;">{{ page.title }}</h1>

    {% if page.role or page.email or page.instagram or page.website %}
    <div style="margin-bottom: 14px; line-height: 1.4;">
      {% if page.role %}<div>{{ page.role }}</div>{% endif %}
      {% if page.email %}<div><a href="mailto:{{ page.email }}">{{ page.email }}</a></div>{% endif %}
      {% if page.instagram %}<div>{{ page.instagram }}</div>{% endif %}
      {% if page.website %}<div><a href="{{ page.website }}">{{ page.website }}</a></div>{% endif %}
    </div>
    {% endif %}

    {% if page.thumbnail %}
    <img src="{{ page.thumbnail | relative_url }}" alt="{{ page.title }}" style="width: 320px; max-width: 100%; height: auto; display: block; margin: 0 0 18px 0;">
    {% endif %}
  </header>

  <div class="post-content">
    {{ content }}
  </div>
</article>
