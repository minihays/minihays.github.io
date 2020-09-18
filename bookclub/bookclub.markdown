---
layout: page
title: Book/Puzzle Club
permalink: /bookclub/
---
Welcome to my Book Club page! The members of book club are avid readers even if they aren't reading our current book. We love to talk about all things book-related and we also really like doing puzzles. We hope you will join us and give your input about current books you are reading, thoughts on the books we are reading, puzzles you are doing or anything else you can think of. I am so glad you are here. 

We pick a book from our [book picks list](/bookclub/booksread/) for each month and meet in person or virtually at the end of each month. We read one book for December/January since we don't meet at the end of December. I try to get books chosen for about 6 months at a time so people have time get on waiting lists if need be. 

Below are the most recent posts from my [@minihaysreads](http://instagram.com/minihaysreads/) Instagram page.

<div id="curator-feed-minihaysreads-layout"><a href="https://curator.io" target="_blank" class="crt-logo crt-tag">Powered by Curator.io</a></div>
<!-- The Javascript can be moved to the end of the html page before the </body> tag -->
<script type="text/javascript">
/* curator-feed-minihaysreads-layout */
(function(){
var i, e, d = document, s = "script";i = d.createElement("script");i.async = 1;
i.src = "https://cdn.curator.io/published/ee27246f-6d85-46ff-839c-4d53c248e1e5.js";
e = d.getElementsByTagName(s)[0];e.parentNode.insertBefore(i, e);
})();
</script>

----
# -Book Blog Posts-
{% for post in site.categories.Books %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}