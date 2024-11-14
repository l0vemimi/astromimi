---
title: post layout formatting
author: mimi
pubDatetime: 2024-11-10T09:00:00Z
slug: post-layout-formattings
featured: false
draft: false
tags:
  - archive
ogImage: ""
description: layout for blog posts
---

## Table of contents

### other elements

other elements are:

1. ogImage

og  image of the post; useful for social media sharing and seo search engine optimisation - default = SITE.ogImage or generated OG image

2. canonicalURL

canonical url absolute, incase the article already exists on other source - default = Astro.site + Astro.url.pathname

1. headings

headings should be in a h2 - h6 format because the blog posts use title as the main heading

4. using table of contents

the toc should be in h2 and worded as "Table of contents" with the capital letter at the start

5. modifying a post

modDatetime should be added with the same iso 8601 format has the publish date time; this should only be added after a post is modified