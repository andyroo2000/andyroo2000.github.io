---
layout: post
title:  "On not using GitHub Pages"
date:   2013-08-02 03:34:46
categories: musings
---

When I started this blog, I was thinking that I would keep it simple and host on GitHub pages.

All you have to do is push your site to a public Git repo with your_username.github.io and [GitHub Pages](http://pages.github.com) will parse the file to build and host your site - very cool!

I tried it and GitHub Pages was immediately serving my site - no complaints.

The trouble came when I tried to integrate CodeKit for SASS preprocessing. I tried several configurations and eventually settled changing the CSS output path to: css_dir = "/_site/css" in the config.rb file.

This is necessary to take advantage of code injection, which is a great benefit of working with CodeKit.

The darkside comes when you want to push your changes to GitHub, since... wait a minute... let me try something before I finish this...