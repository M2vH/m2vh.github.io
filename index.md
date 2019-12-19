<nav>
<!-- <a href="/">Start</a> -->
<a href="/pages/projects.html">Projects</a>
<a href="/about.md">About me</a>
</nav>

---

<p>{{ site.posts | where:"layout","mypost" | post | mardonify}}</p>

<!-- <p>{{ site.posts | where:"layout","post" | content | markdownify }}</p> -->

{% for post in site.posts %}
<p>{{ post.content | markdownify }}</p>
{% endfor %}