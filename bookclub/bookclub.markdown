---
layout: page
title: Books & Reading
permalink: /bookclub/
---
![rainbow](/images/BrightSkinnyRainbow.png)
- **[BOOK CLUB BOOK PICKS LIST](/bookclub/booksread/)** 

Welcome to my little corner about all things book related! I have always been a lover of books and reading since I was very young. I still read all the time and am doing my best to raise kids who love reading and grow up to be readers. I usually have more than one book going at a time in various forms (ebook on my Kindle, a physical book, an audiobook, and a couple books I am reading to the kids or with an individual child). 

Another fun fact is I started a book club many years ago when my oldest was very young. We are nearing 9 years for our little group that has changed and grown over the years. Most of the members of book club are avid readers even if they aren't reading our current book. We love to talk about all things book-related and we also really like doing puzzles! We would love if you wanted to join us and give your input about current books you are reading, thoughts on the books we are reading, puzzles you are doing or anything else you can think of!

We pick a book from our **[Book Picks List](/bookclub/booksread/)** for each month and meet in person or virtually at the end of each month. We read one book for December/January since we don't meet at the end of December. I try to get books chosen for about 6 months at a time so people have time get on waiting lists if need be. 

Currently, our book club is through a [group on Facebook](http://facebook.com/groups/bookwormsandpuzzlepiecers/). We discuss all things books, book club and puzzles. Yes, we like puzzles, too. I also recently learned about Amazon Book Clubs and added [our group](https://www.amazon.com/amazonbookclubs/detail/amzn1.club.bookclub.28ba7cf3-de83-fac6-efe0-4252034d9917?) on there as well. 

I also keep an ongoing [wish list](https://www.amazon.com/hz/wishlist/ls/BX6IO38STJYM?ref_=wl_share) on Amazon of the books I want. Some are listed in paperback form, but usually I get Kindle ones. I like to keep track in case I have any discounts or coupons to use. I also started keeping track of [books for the kids](https://www.amazon.com/hz/wishlist/ls/EY284C689ZRR?ref_=wl_share) that I want to get them or read with/to them. I also keep track of books I have read on [Goodreads](https://www.goodreads.com/user/show/2648038-andi) if you want to be friends there.

Below are the most recent posts from my [@minihaysreads](http://instagram.com/minihaysreads/) Instagram page where I post about all things book related and post reviews of books I have read.

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

![header](/images/BrightSkinnyRainbowHeader.png)

# -All The Book Blog Posts-
{% for post in site.categories.Books %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}