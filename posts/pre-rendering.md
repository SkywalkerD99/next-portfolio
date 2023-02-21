---
title: "Two Forms of Pre-rendering"
date: "2020-01-01"
---

Next.js has two forms of pre-rendering methods: **Static Generation** and
**Server-side Rendering**. The dirrerence is in **when** it generates the
HTML for a page.

- **Static Generation** is the pre-rendering method that generates the HTML at
  **build time**. The pre-rendered HTML is then _reused_ on each request.
- **Server-side Rendering** is the pre-rendering method that generates the HTML
  on **each request**.

Importantly, Next.js lets you **choose** wich pre-rendeing form to use for
each page. You can create a "hybrid" next js app by using Static Generation
for most pages and using Server-side Rendering for others.
