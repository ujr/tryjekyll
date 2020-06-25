---
layout: post
author: me
permalink: /specialpost
categories: testing
---

The **permalink** is the output location of a post or page.
It is controlled by the `permalink` setting in *\_config.yml*
and can be overridden by `permalink: foo` in the front matter.

Note that the default permalink setting includes the
category hierarchy, so that a post with `categories: foo bar`
in the front matter will be published at */foo/bar/Y/M/D/title.ext*.

This may be useful, but I'd rather like to omit the output extension.
To do so, set

    permalink: /:categories/:year/:month/:day/:title

(without `:output_ext`) in *\_config.yml* (and restart the local server).

**NB.** This post overries the permalink in its frontmatter.

