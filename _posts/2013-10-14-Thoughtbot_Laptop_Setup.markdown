---
layout: post
title:  "Thoughtbot Laptop Setup"
date:   2013-10-14 22:55:47
categories: musings
---

After seeing a very impressive screencast by Thoughtbot on CodeSchool, I decided to try [Thoughtbot Prime](https://learn.thoughtbot.com). This was maybe a little premature, as Thoughtbot is primarilty concerned with teaching Rails and I'm currently in the middle of intense preparation for my coding interview with [HackReactor](http://hackreactor.com) which is going to be in JavaScript.

However, when I need a break from my Javascript studies, I watch Thoughtbot's Advanced Ruby videos. I've also started going through some Rails tutorials in my spare time. I was hitting some snags with my Rails dev environment, due to the haphazard way I had installed many gems and versions of Ruby. Additionally, I had made some modifications to my shell (before I knew what I was doing) which produced some unexpected consequences. This had me thinking about wiping my laptop and installing everything in a more methodical way. I set my computer to reinstall OSX and xCode overnight after backing up my personal documents and dotfiles.

This next part may seem unrelated, but stick with me here... After signing up for Thoughtbot Prime, you gain access to their private GitHub repository. There are tons of useful things there, but I immediately noticed one called 'laptop'. 'Laptop' in their words is: "A shell script which turns your Linux or Mac OS X laptop into an awesome development machine." Additionally, there is a repo call 'dotfiles' that contains their default dotfiles for Vim, zsh, git and tmux. Fortunately, the dotfiles are pretty minimal and I didn't find myself having to override a bunch of settings (unlike the Vim distro [spf13](https://github.com/spf13/spf13-vim), which made entirely too many decisions for my taste).

For me, the Thoughtbot laptop and dotfiles are the perfect balance of sensible defaults and blank slate (*+1 for mapping ctrl-a and Vim motion keys to navigate tmux windows*). Some of their decisions introduced me to new tools, as well. I had been using Pathogen, but I'm finding [Vundle](https://github.com/gmarik/vundle) to be much easier for managing Vim plugins. Starting with a clean slate also caused me to check out [AutoPairs](https://github.com/jiangmiao/auto-pairs), which is working much better than the script I was using before.

Now it's back to learning JavaScript for me!
