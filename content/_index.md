---
title: Home
sections:
  - section_id: hero
    component: hero_block.html
    type: heroblock
    content: >-
      This section can contain a subtitle or tagline. The recommended length is
      one to three sentences, but can be changed as you prefer.
  - section_id: about
    component: content_block.html
    type: contentblock
    title: About
    content: >-
      I love spending time with my family. We play a lot of both board games and video games together. When we’re not doing that, I’ll probably be programming in Rust (my favorite language), playing Hollow Knight or Rocket League, or maybe even playing D&D.

      I feel like my strengths are mainly in systems programming, but right now I’m doing web eLearning development with StateFoodSafety. I’m a student at Utah Valley University going for a Bachelor’s degree in Computer Science, and I’ve got a little over a year left there.
    actions:
      - label: About Me
        url: /about
      - label: Contact Me
        url: /contact
  - section_id: recent-posts
    component: posts_block.html
    type: postsblock
    title: Recent Posts
    num_posts_displayed: 4
    actions:
      - label: View Blog
        url: blog/index.html
layout: home
menu:
  main:
    weight: 1
    name: Home
---
