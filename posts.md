<nav>
<a href="/">Start</a>
<a href="/">Somewhere else</a>
</nav>

---

{% for post in site.posts %}
<p>{{ post.content | mardownify }}</p>
{% endfor %}