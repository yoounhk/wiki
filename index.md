{% for page in site.pages %}
  <article>
    <h2>
      <a href="{{ page.url }}">
        {{ page.title }}
      </a>
    </h2>
  </article>
{% endfor %}