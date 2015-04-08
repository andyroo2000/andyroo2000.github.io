---
layout: post
title:  "Stuff you should know about Emmet"
date:   2014-08-01 21:29:46
categories: musings
---

In the section about installing a text editor, I mentioned that you should install [Emmet](http://emmet.io).

I am of the opinion that typing HTML tags is a big waste of time for dumb jerks. If you write any amount of HTML, you can save a lot of time and reduce typing errors by learning to take advantage of Emmet's shortcut syntax.

You don't necessarily need to know every shortcut on the Emmet [cheatsheet](http://docs.emmet.io/cheat-sheet), but there are a few shortcuts that are so incredibly useful, that you should stop whatever you're doing and learn them right now.

## !

`!` is probably one of the biggest timesavers when you're first starting out. Just type `!` and hit the **tab** key and you'll get a skeleton of an HTML5 page structure, which looks something like this:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <title>Document</title>
</head>
<body>

</body>
</html>
```

## . and \#

Next, you'll want to learn how to add classes and ids to HTML elements using Emmet. Say you want to add a div with an id of **container**...

If you type `div#container` and hit the **tab** key, you'll get: 
```html
<div id="container"></div>
```
and the cursor will be inserted between the opening and closing tags.

If you wanted an image with a class of **gallery**, you could type `img.gallery` and hit the **tab** key to get:
```html
<img class="gallery"></img>
```

## *

The `*` character multiplies whatever came before it. So if you type `li*5` and hit the **tab** key, you'll get:

```html
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
```

## >

The `>` character allows you to nest HTML elements. For example, if you type `ul>li` and hit our trusty **tab** key, you'll get:

```html
<ul>
  <li></li>
</ul>
```

Event better, you can combine this with the `*` character to do something like `ul>li*5`, which would give you:

```html
<ul>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
</ul>
```

## Go find you're own shortcuts

These are just a few of the Emmet shortcuts that I use daily, but I highly recommend spending a half hour to an hour checking out the [Emmet Cheat Sheet](http://docs.emmet.io/cheat-sheet) and trying things out for yourself.

Then pick a few that you think might be particularly useful for you and write them down or put them in a notes file or something that you can refer to later.

For each of my languages or programming environments, I keep a text file that has keyboard shortcuts that I'm trying to learn. I don't necessarily try and learn a million, but I find the ones that seem most useful and try and use them often enough to really learn them. 