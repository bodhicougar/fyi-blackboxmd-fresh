---
title: Home
sections:
  - actions:
      - label: JAMstack
        url: 'https://jamstack.org/'
    component: HeroBlock
    content: >-
      Why the Jamstack?


      Better Performance


      Why wait for pages to build on the fly when you can generate them at
      deploy time? When it comes to minimizing the time to first byte, nothing
      beats pre-built files served over a CDN.


      Higher Security


      With server-side processes abstracted into microservice APIs, surface
      areas for attacks are reduced. You can also leverage the domain expertise
      of specialist third-party services.


      Cheaper, Easier Scaling


      When your deployment amounts to a stack of files that can be served
      anywhere, scaling is a matter of serving those files in more places. CDNs
      are perfect for this, and often include scaling in all of their plans.


      Better Developer Experience


      Loose coupling and separation of controls allow for more targeted
      development and debugging, and the expanding selection of CMS options for
      site generators remove the need to maintain a separate stack for content
      and marketing.
    section_id: hero
    title: My portfolio
    type: heroblock
  - actions:
      - label: Contact Me
        url: /contact
    component: ContentBlock
    content: >-
      Cloud Solution Architect for the Social Media Era: organizing entities
      strategically.
    image: /images/jamstack-full-logo.svg
    section_id: about
    title: About
    type: contentblock
  - actions:
      - label: View Blog
        url: blog/index.html
    component: PostsBlock
    num_posts_displayed: 4
    section_id: recent-posts
    title: Recent Posts
    type: postsblock
menus:
  main:
    identifier: home_start
    title: Home
    weight: 1
template: home
---

