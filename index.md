---
---
{% assign pages_list = site.pages | sort:"order" %}
{% for node in pages_list %}
{% if node.title != null %}
<li><a class="{% if page.url == node.url %}active{% endif %}" href="{{ site.baseurl }}{{ node.url }}">{{ node.title }}</a></li>
{% endif %}
{% endfor %}
