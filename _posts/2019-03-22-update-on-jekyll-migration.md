---
excerpt: By George, I think I've got it!
layout: post
title: Update on my migration to GitHub
---
As I tested different things out I was able to discover that part of the problem was that GitHub Pages needed to know just a bit more about my site. First I added a base_url, which broke my local site. It did get GitHub Pages to show the paginated index pages with the theme. However, the links to the posts were still broken. I removed the base_url and defined the url. I also added a CNAME record and pointed my DNS to vegantriathlete.github.io. Now things looks much better. I've got to wait a bit for GitHub Pages to be able to serve my site over https, though. I'll check back tomorrow.

Bhavatu sabba mangalam - May all beings be happy
