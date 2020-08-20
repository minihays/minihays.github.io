---
layout: page
title: Book/Puzzle Club
permalink: /bookclub/
---
Welcome to my Book Club page! The members of book club are avid readers even if they aren't reading our current book. We love to talk about all things book-related and we also really like doing puzzles. We hope you will join us and give your input about current books you are reading, thoughts on the books we are reading, puzzles you are doing or anything else you can think of. I am so glad you are here. 

We pick a book for each month and meet in person or virtually at the end of each month. We read one book for December/January since we don't meet at the end of December. I try to get books chosen for about 6 months at a time so people have time get on waiting lists if need be. 

----
# [Monthly Book Picks](/bookclub/booksread/)
# [Little Library Love](http://127.0.0.1:4000/books/lfl/2020/08/03/little-library-love.html)

----
# Book-related Blog Posts:
{% for post in site.categories.Books %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}