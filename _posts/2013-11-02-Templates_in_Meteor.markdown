---
layout: post
title:  "Templates in Meteor"
date:   2013-11-02 21:21:17
categories: musings
---


Over the past day or two, I've been diving into [Meteor.js](http://www.meteor.com). The [docs](http://docs.meteor.com/) are actually pretty good, but I thought I'd be fancy and go through the tutorial on NetTuts and also check out the book, [Getting Started with Meteor.js](http://www.packtpub.com/getting-started-with-meteor-javascript-framework/book).

Nothing against either of those resources, but I felt that I had skipped over some of fundamental concepts of how Meteor works. This is probably due to my lack of experience with Backbone.js, Handlebars, and MongoDB, which are major components of Meteor.

In any case, after watching several excellent and very simple YouTube tutorials, everything began to make sense. The problem with many of the tutorials I was using was that they used *identical* or *very similar* variable names, function names, and template names, so I could see that everything was working, but I really couldn't understand how the data was flowing. (Again, this is largely due to my lack of experience with Handlebars or Jade)...

So, for anyone else who is on their first day or two of trying out Meteor, I present the most simple example of how date from a function in the .js file is passed to the template in the .html file:

{% gist 7292770 %}

{% gist 7292729 %}

This is from an [example](http://youtu.be/HAcN3JyQoyY) by one of the creators of Meteor. This particular bit of code will check to see if the app is connected to the server and display a status message on the client.

* The most important thing inside "`if(Meteor.isClient)`" is "`Template`", which tells Meteor that were talking about templates.

* The second thing after that is "`.connected`." This tells meteor that were talking about the "`<template name="connected">`."

* The thing after that is "`.connection_state`." This is kind of like an argument that we can then use to call the function inside the html template via "`{{ connection_state }}`."

Hopefully, this helps someone else out who is just starting with Meteor and having a hard time understanding how to get data from the javascript file into the template.