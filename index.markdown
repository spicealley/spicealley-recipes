---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<section class="search-result-section">
{% for post in site.posts %}
  <article class="search-result">
    <a href="{{ post.url | relative_url }}" class="search-result-title">{{ post.title }}</a>
    <div>{{ post.excerpt }}</div>
  </article>
{% endfor %}
</section>
