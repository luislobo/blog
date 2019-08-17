---
title: "That is a very nice and simple way of adding caching into your routes."
description: "You could use Redis or Memcache if you need/want to persist your data across different node instances."
date: "2017-08-14T14:18:17.250Z"
categories: []
published: true
canonical_link: https://medium.com/@luislobo/that-is-a-very-nice-and-simple-way-of-adding-caching-into-your-routes-84d2bd040b1a
redirect_from:
  - /that-is-a-very-nice-and-simple-way-of-adding-caching-into-your-routes-84d2bd040b1a
---

That is a very nice and simple way of adding caching into your routes. One thing that needs to be said though, you should not add to all of them, not necessarily all GET requests return the same result for the same URL. Imagine a GET that returns “latest 10 articles bought by customers”. The URL might be the same but the result would vary in time.

You could use Redis or Memcache if you need/want to persist your data across different node instances.
