---
layout: post
title:  "Thoughtbot Laptop Setup"
date:   2013-10-14 22:55:47
categories: musings
---

After seeing a very impressive screencast by Thoughtbot on CodeSchool, I decided to try [Thoughtbot Prime](https://learn.thoughtbot.com). This was maybe a little premature, as Thoughtbot is primarilty concerned with teaching Rails and I'm currently in the middle of intense preparation for my coding interview with [HackReactor](http://hackreactor.com) which is going to be in JavaScript.

However, when I hit a temporary wall in my Javascript studies, I've been enjoying Thoughtbot's Advanced Ruby videos and I'm getting reacquainted with Rails. Of course, this is making me regret all of the monkeying around that I've done with my development environment... things that were not installed in a careful manner and various shell modifications that seemed really cool, but that were having unintended consequences as I started to pile installations on top of each other.

After signing up for Thoughtbot Prime, you gain access to their private GitHub repository. There are tons of useful things there, but I immediately noticed one called 'laptop'. 'Laptop' in their words is: "A shell script which turns your Linux or Mac OS X laptop into an awesome development machine." Additionally, there is a repo that contains their default dotfiles for Vim, zsh, git and tmux. Fortunately, the dotfiles are pretty minimal and I didn't find myself having to override a bunch of settings or not understanding what was in the file (unlike the Vim distro [spf13](https://github.com/spf13/spf13-vim), which made entirely too many decisions for my taste).

I haven't yet felt the need to go crazy customizing my shell, but I think it's important to keep building my .vimrc and .tmux.config rather than just pasting a bunch of settings in and not understanding how anything works. For me, the Thoughtbot laptop and dotfiles are the perfect balance of sensible defaults and blank slate. Some of their decisions introduced me to new tools, as well. I had been using Pathogen, but I'm finding [Vundle](https://github.com/gmarik/vundle) to be much easier for managing Vim plugins. This moment of plugin introspection also caused me to try [AutoPairs](https://github.com/jiangmiao/auto-pairs), which is working much better than the script I was using before.
