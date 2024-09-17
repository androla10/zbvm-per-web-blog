---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Initialization with Temporal IO!
publishDate: 05 Nov 2023
name: Zeler Villarreal
description: Just a Hello World Post!
---

<Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />

Hello my friends, in this tutorial. I teach to the best practice with temporal IO.

Para este ejemplo estaremos utilizando la siguiente documentación que se encuentra en su misma página de temporal.
