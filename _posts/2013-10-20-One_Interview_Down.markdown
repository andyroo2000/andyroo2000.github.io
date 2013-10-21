---
layout: post
title:  "Thoughtbot Laptop Setup"
date:   2013-10-14 22:55:47
categories: musings
---

Although I'm currently in the middle of intense preparation for my coding interview with [HackReactor](http://hackreactor.com) which is going to be in JavaScript, I've been lightly experimenting with Ruby on the side.

I've watched Thoughtbot's Advanced Ruby video and had started the Hartl rails tutorial. Unfortunately, I was hitting some snags due to the haphazard way I had installed many gems and versions of Ruby. There was also some weirdness in my shell, as a result some customization I had done before I really knew anything about the Terminal. Things were just a bit of a mess. This got me thinking about wiping my laptop and installing everything in a more methodical way. Knowing that I would lose about a day of productivity, I set my computer to reinstall OSX and xCode overnight after backing up my personal documents and dotfiles and prepared myself for a day of installing software.

After signing up for Thoughtbot Prime, I began checking out their GitHub profile. There are tons of useful things there, but I immediately noticed one called [laptop](https://github.com/thoughtbot/laptop). Laptop is (in their words): "A shell script which turns your Linux or Mac OS X laptop into an awesome development machine." You just run the script from the command line and it goes crazy installing things for about 8 minutes. Additionally, there is a repo called [dotfiles](https://github.com/thoughtbot/dotfiles) that contains Thoughtbot's default dotfiles for Vim, zsh, git and tmux. Fortunately, the dotfiles are pretty minimal and I didn't find myself having to override a bunch of settings (unlike the Vim distro [spf13](https://github.com/spf13/spf13-vim), which made entirely too many decisions for my taste).
