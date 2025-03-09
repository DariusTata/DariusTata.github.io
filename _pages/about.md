---
permalink: /
title: "🏠Home"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Landing Page

### Latest Blog Post

{% assign latest_post = site.posts.first %}
**[{{ latest_post.title }}]({{ latest_post.url }})**  
*Published on {{ latest_post.date | date: "%B %d, %Y" }}*  

{{ latest_post.excerpt }}  
[Read more →]({{ latest_post.url }})
