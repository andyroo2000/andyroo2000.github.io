---
layout: post
title:  "On Using CodeKit + GitHub Pages"
date:   2013-08-02 03:34:46
categories: musings
---

It took a minute to wrap my head around, but I finally have this working pretty well.

There was a little bit of initial conflict between CodeKit trying to rewrite files on 'save' and Jekyll rebuilding files that CodeKit just created.

The thing is that I want to take advantage of instantaneous code injection from CodeKit, which only works if the CSS file it's creating is the one that is referenced by the page running on my local server.

The obvious solution is to open the config.rb file and change the output path from the 'css' folder to '_site/css'. This is great, but not so much when I push to GitHub and the stylesheets in the 'css' folder haven't been updated (as those are the ones that GitHub Pages is looking at to build the site).

But after some poking around, I discovered that everything works pretty well if from the terminal, you type:

{% highlight bash %}

jekyll serve --watch

{% endhighlight %}

The responsiveness isn't quite as smooth as having CodeKit modify the _site/css file directly, but when CodeKit modifies the /css file, the Jekyll server rebuilds the _site/css file which then causes CodeKit to use its code injection in the browser.

It's a bit convoluted, but it actually works pretty well and when I push to GitHub, my files are served as they should be.

