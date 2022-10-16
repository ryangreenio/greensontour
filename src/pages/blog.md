---
layout: blog.njk
title: Articles
date: 2022-01-01
pagination:
  data: collections.post
  size: 20
permalink: "blog{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber }}{% endif %}/index.html"
metaDescription: Read our awesome blog to get travel tips, guides and insights from two full-time digital nomads. We document our adventures around the world.
subtitle: A collection of our insights and tips!
image: /src/assets/img/couple-photo.webp
eleventyNavigation:
  key: Blog
  order: 2
---
