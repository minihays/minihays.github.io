---
layout: page
title: Robotics
permalink: /robotics/
---

![Lego Header](/images/FIRST.jpeg)

For the 2022-2023 school year, my husband (Chuck) and I started a robotics program at our local Middle School (5th-7th graders). We met with district and community education staff to brainstorm, plan all the details, work out kinks and put together this program. The hope is for these middle schoolers to get excited about robotics and coding/programming and want to continue on in High School where were have an active robotics program. 

We use products/kits from [FIRST LEGO League](https://www.firstinspires.org/robotics/fll/what-is-first-lego-league). We chose to do work with LEGO because kids enjoy them and we hoped that putting something they enjoy along with something they might not be familiar with would excite and interest more kids. 

We currently have openings for 20 students (which is 2 teams of 10 students) and our first year we had a waitlist!

We learned so much our first season working with the kids at this level (we have previously done groups at the elementary level when our kids were younger) and we have some changes to make this season to make it even better. We hope to continue to make this a program that kids are excited about and want to return to. Overall, we want them to have fun and find and continue to grow an interest/love of robotics, coding and programming.

**<span style="text-decoration: underline">About The Coaches:</span>**
* Andi is a self proclaimed steminist and has a passion for getting girls interested and involved in the STEM fields. She works as an office specialist at a local law firm, subs in the school district, is an avid reader, enjoys fishing and lake sports, is a newby woodworker and does some website development and programming on the side. 

* Chuck works for Google as a software engineer and has worked on various projects including Duo and Meet. He previously worked for Microsoft, has built and competed in local robotics competitions and helped found a company of throwable robots during grad school. He also coaches youth sports, is a project extraordinare, and enjoys fishing and lake sports.

I will also be posting photos and updates on one of my Instagram pages as well: [@technicallyscattered](https://www.instagram.com/technicallyscattered/). We are looking forward to a great second season!

![header](/images/SkinnyRainbow.jpg)

# - All The Robotics Blog Posts -
{% for post in site.categories.Robotics %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}