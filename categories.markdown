---
layout: page
title: Blog Categories
permalink: /blogcategories/
---
----
# <span style="text-decoration: underline">All Things Books</span>
{% for post in site.categories.Books %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
<br />
# <span style="text-decoration: underline">All Things COVID</span>
{% for post in site.categories.COVID %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
<br />
# <span style="text-decoration: underline">All Things Kids</span>
{% for post in site.categories.Kids %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
<br />
# <span style="text-decoration: underline">All Things Lake</span>
{% for post in site.categories.Lake %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
<br />
# <span style="text-decoration: underline">All The Randomness</span>
{% for post in site.categories.Randomness %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
<br />
# <span style="text-decoration: underline">All Things Tech</span>
{% for post in site.categories.Tech %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}




