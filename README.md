Guidelines for developing MyUW portlets with panache.

Public Repo but Unapologetically my.wisc.edu Focused
====================================================

Heads up!  This here is a public repo.  It is public to facilitate transparency and collaboration with peer portlet-developing outfits.

However, this guide is unapologetically MyUW-focused.  It's a guide for how we aspire to develop portlets around here for our portal.

We hope that what's good in this guide can assist, inspire, and support others in also developing better portlets, and we hope you'll help us to understand how our guide can be better and can help us develop better, but ultimately this right here is our guide for us, and you may need a guide that's different for you, and *that's okay*.  In fact, making this a public repo on GitHub makes forking oh so easy.  Have at.

Vision
======

Motivation
----------

We're [redesigning](http://redesign.my.wisc.edu/) [my.wisc.edu](https://my.wisc.edu) to be more awesome.  One aspect of making it more awesome is making our portlets more consistently awesome, and we hope to be able to understand and document ways to do that to support continuous improvement.

Scope
-----
The `portlet-guide` will advise about developing portlets, suggesting `CSS` and markup usages, caching practices, API usages, etc., that will make the portlet thrive in our portal.

Examples of in-scope topics:
* Producing markup that plays nicely in a portal
* Using `CSS` styles that play nicely in a portal
* Namespacing your `JavaScript` to play nicely in a portal
* UI conventions to look good and be highly usable in the portal
* Versioning, Maven build, and especially entity file practices *as they relate specifically to playing nicely in the portal*


Not in scope
------------
This is *not* a general Java development guide and is not intended to comment on anything that's not particularly about developing a *Portlet*.

Examples of not-in-scope topics:
* Using the right kind of whitespace in your source code
* How to name your Java classes
* Excellent source control commit message formatting practices

portlet-guide and (the putative) portal-guide
-------------------------------------------
Current vision is to have complementary `portlet-guide` and `portal-guide` projects, so that developers of a portlet intended to build a webapp not delivered as part of the portal `.war` itself can have a style guide focused on that need.

The `portal-guide` would include by reference this `portlet-guide` and then work from there advising about what's special about developing portal infrastructure.

The `portal-guide` doesn't exist yet.


Implementation Notes
=====================

* `HTML` source in GitHub repository
* Generate website via Jekyll
* Website hosting via GitHub pages
* Since it's Git / GitHub driven, Pull Requests and change management are a win.

TODO:
* Factor out content into multiple files rather than one giant `index.html` file.
* Use `Markdown` rather than `HTML` for some of the content where appropriate.
* Demonstrate highlighted source code example inclusions (which should be eminently feasible since the `Code Guide` that inspired this demonstrates doing that).

Acknowledgements
=================

Inspired by [Code Guide](http://mdo.github.io/code-guide/).

See also `ACKNOWLEDGEMENTS.md` accompanying.
