---
layout: post
title:  "Jekyll Default Styling"
date:   2013-08-06 05:34:46
categories: musings
---

So far, I have to say that I'm enjoying my [Jekyll](http://jekyllrb.com/) experience.

It's lightweight and easy to understand and I'm looking forward to digging into [Liquid](http://wiki.shopify.com/Liquid) and modifying the information on my page a bit more.

The only thing that's a little curious to me is that the default styling is so aggressively bad. Things are set to pixel widths and while the default html structure uses the html5 style doctype, there are unsemantic div tags all over the place. Not that it's hard to replace them with their semantic html5 equivalents: `<header>, <footer>, <section>, <article>` etc. It just seems funny to have all of these presentational divs for something that doesn't seem overly concerned with presentation in the first place.

I really can't knock this thing though. In a way, it's cool that the default style is so terrible, because you don't hesitate to throw out all the styles and start from scratch.