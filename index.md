<nav>
<!-- <a href="/">Start</a> -->
<a href="/pages/projects.html">Projects</a>
<a href="/about.md">About me</a>
</nav>

---

{% for post in site.posts %}
<p>{{ post.content | mardownify }}</p>
{% endfor %}