---
layout: page
title: About
permalink: /about/
---

This is my first attempt at using [Jekyll][jekyll].
I was following the tutorial
[Make a Static Website with Jekyll][tutorial]
at [www.taniarascia.com][taniarascia].
Further experimentation may follow.

After adding a few posts (taken from
[Jekyll's Step by Step Tutorial][blogging])
note the posts's URLs: /Y/M/D/title.html for those newly added,
*vs* /jekyll/update/Y/M/D/title.html for the default post.
Apparently, the `categories` from the post's front matter
enter the permalink. Read on [Permalinks in the docs][permalinks].

This is the about page.
It uses the **{{ page.layout }}** layout
and lives in *\_pages/01\_about.md*

[tutorial]: https://www.taniarascia.com/make-a-static-website-with-jekyll/
[taniarascia]: https://www.taniarascia.com/
[jekyll]: https://jekyllrb.com/
[blogging]: https://jekyllrb.com/docs/step-by-step/08-blogging/
[permalinks]: https://jekyllrb.com/docs/permalinks/

