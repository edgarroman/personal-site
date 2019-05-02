---
title: 'Blog Setup'
date: 2019-05-02T15:50:10-04:00
draft: false
tags: ['blog', 'blogging', 'hugo']
summary: 'How I setup my personal blog'
---

### Essentially:

-   [Hugo](https://gohugo.io/)
    -   Basically only needed to install the Hugo binary. And then off to the races. Extremely minimal
        dependencies.
-   From scratch theme based on [Bootstrap 4](https://getbootstrap.com/)
    -   Hardest part is picking a theme. Lots of good ones out there, but generally limited customization. So
        I started with the generic framework and moved forward from there. Also allowed me to understand the
        Hugo templating system and relationships
-   Hosted on [github](https://github.com/edgarroman/edgarroman.github.io)
    -   Free and source controled. Why not?
-   Some customizations
    -   Created shortcode to show [markdown output and code](/blog/2019/markdown-examples/)

### Still need to do:

-   Continue to tweak design
    -   This is a never ending process
-   Implement client side search
    -   Once there is enough content for that
-   Implement automated builds
    -   So that once I check in a post, it is auto published
    -   https://willschenk.com/articles/2018/automating_hugo_with_circleci/

### Other interesting setups

-   https://flaviocopes.com/stack/
