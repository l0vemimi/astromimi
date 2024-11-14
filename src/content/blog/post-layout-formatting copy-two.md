---
title: post layout formatting two
author: mimi
pubDatetime: 2024-11-14T12:00:19Z
slug: post-layout-formatting-two
featured: true
draft: false
tags:
  - archive
ogImage: ""
description: layout for blog postst two
---

## Table of contents

### other elements

other elements are:

1. ogImage

og  image of the post; useful for social media sharing and seo (search engine optimisation)

**default = SITE.ogImage or generated OG image**

2. canonicalURL

canonical url (absolute), incase the article already exists on other source

**default = Astro.site + Astro.url.pathname**

### headings

**headings should be in a h2 - h6** format because the blog posts use title as the main heading

### using table of contents

the toc should be in h2

### modifying a post

modDatetime should be added with the same iso 8601 format has the publish date time; this should only be added after a post is modified