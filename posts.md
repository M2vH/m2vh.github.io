{% for post in site.posts %}
<p>{{ post.content | mardownify }}</p>
{% endfor %}