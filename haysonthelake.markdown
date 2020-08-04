---
layout: page
title: Hays On The Lake
permalink: /haysonthelake/
---
In the Spring of 2019, we bought a boat again. We had one years ago and sold it. We wanted to get a boat and see if it worked with our lives and that the kids enjoyed it. We discussed getting a cabin for years and were starting to feel like that was something we wanted to pursue. After lots of pros/cons lists, we realized that a cabin might not work well for our schedules and what we wanted.

So during the summer of 2019, we started searching for houses and properties for sale on Lake Minnetonka. We had lived on an island on the lake years ago in our pre-kid years and loved living out there. But we decided to move to another city instead of staying by the lake. We knew we loved the area we used to live and started doing a lot of looking at homes for sale. We ended up finding a lot we liked during the summer and eventually bought it during the winter. Then started the process of tearing down a house and building a house for us. A bit of this adventure has been documented on an Instragram page I made: [@haysonthelake](http://instagram.com/haysonthelake).

Here are our adventures! 

# Lake-related Blog Posts:
{% for post in site.categories.Lake %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}