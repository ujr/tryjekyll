---
layout: post
title: Collections
author: me
---

Collections in Jekyll are documents that live a root-level
folders *\_CollectionName*, e.g., `_authors`. Each document
in this author will be available to Liquid through `site.authors`,
which can be used to generate an *Authors* page.

Using Liquid filtering it is possible to add a list of post
to each author's page, and also to link from a post to its author.

See the [Collections in the Step by Step Tutorial][collections].

Similarly, a page with all categories could be built.

**NB.** This approach is driven by the files in the
collection folder, *not* by the properties in the
frontmatter of the posts. (Could this be done as well?
Probably, read up on Variables and Liquid in the docs.)

[collections]: https://jekyllrb.com/docs/step-by-step/09-collections/

