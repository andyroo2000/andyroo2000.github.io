---
layout: post
title:  "Getting Started"
date:   2014-08-01 21:33:46
categories: musings
---

## Your code, your text editor

[Sublime Text 3](http://www.sublimetext.com/3) is the text editor that I recommend using. There are many text editors for coders and people tend to have strong opinions about them, but I'm recommending Sublime Text because it's very beginner friendly, yet still very powerful, and because it's really a great text editor. Because it is so popular, there are [tons](https://sublime.wbond.net/browse/popular) of great plugins that extend the functionality. Again, don't overthink this... Sublime is an excellent editor and there are more important things to worry about right now.

Speaking of extending the functionality of Sublime Text, the first thing you should do after installing it, is to install [Package Control](https://sublime.wbond.net/installation). This makes it extremely easy to install plugins. This is completely necessary, so do this immediately.

To get started I recommend finding out how to install a Sublime Text plugin using Package Controll (Google it!) and install the following packages:

- [Emmet](https://sublime.wbond.net/packages/Emmet) can save a lot of time when writing HTML and CSS. I recommend watching the video [demo](http://emmet.io) and referring back to the [cheat sheet](http://docs.emmet.io/cheat-sheet) in order to take advantage of the most useful shortcuts.

- [Sidebar Enhancements](https://sublime.wbond.net/packages/SideBarEnhancements) is not absolutely necessary, but makes the sidebar much more useful.

- [Sublime Code Intel](https://sublime.wbond.net/packages/SublimeCodeIntel) adds much better auto-completion to Sublime Text. Aside from being quicker, using auto-completion (when possible) is a great way to reduce typos.

- [Bracket Highlighter](https://sublime.wbond.net/packages/BracketHighlighter) makes it easier to see pairs of matching brackets and give you a better visual cue when your cursor is between a pair of brackets. The screenshots on their site should give you an idea of what this plugin does.

- [jQuery](https://sublime.wbond.net/packages/jQuery) is a plugin that will allow Sublime Text to autocomplete jQuery methods for you. You might not even know exactly what that means right now, but it will come in handy when we start learning jQuery. Again, not strictly necessary, but I'm in favor of anything that does grunt work for you.

- [AutoFileName](https://sublime.wbond.net/packages/AutoFileName) will allow Sublime Text to autocomplete file names of other files in your project. This will be extremely useful when linking to files, as computers are very unforgiving of typos. Again, this one might not seem so useful now, but you will come to appreciate it later. Definitely look at the instructions for this one as the autocomplete requires a key-command of `ctrl-space` to work.

- [Advanced New File](https://sublime.wbond.net/packages/AdvancedNewFile) adds the ability to create a new directory and name your file all without touching your mouse. This may seem like a small optimization, but you will save a lot of time if you get used to using this feature. Again, you'll have to consult the documentation for instructions, as a special key-command is required to use Advanced New File.

- [Dayle Reese Color Schemes](https://sublime.wbond.net/packages/Dayle%20Rees%20Color%20Schemes) is entirely optional, but it's a nice little collection of color schemes for Sublime in one easy-to-install bundle.

- [Sublime Linter](http://www.sublimelinter.com/en/latest/installation.html) is going to be your new friend. It will automatically check your code as you are typing and point out the errors you are making. This is going to be the trickiest on for you to install, so block off a little time to make sure you get this one installed correctly. You'll have to install Sublime Linter and then install [SublimeLinter-jshint](https://github.com/SublimeLinter/SublimeLinter-jshint), which will specifically tell you when you have errors in your JavaScript.

If you want to see someone explain some Sublime Text power-user stuff in video form, please check out the excellent tutorial on Tuts+, [Perfect Workflow in Sublime Text 2](http://courses.tutsplus.com/courses/perfect-workflow-in-sublime-text-2). You might not absorb everything in the videos, but it will give you a sense of what is possible when you master your text editor. FYI, the video is free to watch after you sign up for a free account with Tuts+.


# Get Ready to Control Your Source Code With Git

The next thing you should install on your computer is [Git](http://git-scm.com).

The installation process will be different, depending on whether you are on a Mac, Linux or a PC. In any case, there are many GUI versions of Git that make using Git much easier to use for beginners. Unfortunately, we will not be using those. I am going to ask that you use the command line version of Git. On Windows, this will be in an application called Git Shell or something similar.

There are several reasons that we will be using the command line:

- It's not *actually* that hard, once you get the hang of it.

- This is how **I** use Git and I can't teach you how to use the graphical version, as I'm not *that* familiar with it.

- I think the majority of serious developers primarily use the command line version of Git, so you will be in good company.

- If you ever get into trouble and need to search [Stack Overflow](http://stackoverflow.com) for help with Git, you will find **way** more results showing you the correct way to do something using the command line.

- It will help you get over your fear of the command line, which is an important rite of passage for any aspiring developer.


## What is Git? (in a nutshell)

Git is a program written by [Linus Torvalds](http://en.wikipedia.org/wiki/Linus_Torvalds) (also the creator of [Linux](http://en.wikipedia.org/wiki/Linux)) which was released in 2005.

To explain everything that Git does is beyond the scope of this guide, but here are the main features that you will use from the beginning:

- It allows you to save snapshots of your code, which can be accessed at any point in the future. You create named save-points (called: **commits**) and you can revert your code back to any of those points whenever you want.

- It has many features which make it easy for large teams of developers to work on the same codebase at the same time.

- If you are working on fixing a bug or adding a feature, you can create a **branch** for the feature, work on your code, send it to other developers for review and then merge it into the **master branch** when it's ready for prime-time.

To get a hand-held brief introduction to Git, I recommend spending about 5 to 10 minutes of light Googling and then checkout the free course on CodeSchool, called [Try Git](http://codeschool.com/courses/try-git). CodeSchool has a more advanced course, if you're a subscriber, but it's unnecessarily advanced for you right now... Just do the free one and move on.


## Get on GitHub

If you haven't already, sign up for an account on [GitHub](http://github.com). Pick a good username. It can be funny, but preferably nothing too obscene, as your GitHub profile is going to become your resume when you begin looking for programming jobs. As someone with no professional programming experience, your actual resume won't help you too much, but if you have a decent amount of good code on GitHub, you stand a chance of getting some sweet job offers.

It might take a little while to see what the fuss is about, but trust me... Github is AMAZING! On the surface, it's a very utilitarian looking site that seems to handle a straightforward task of hosting your source code online. As you progress, you will find out about some of the really cool things that GitHub makes possible. I could tell them to you at the beginning, but I'd rather save them for later, so I can reveal them Usual Suspects style.

Google GitHub and spend about 5 to 10 minutes trying to understand roughly what GitHub is for. Doing a *tiny* bit of research on your own can help give context to these new tools you're learning about.

**WARNING:** Avoid the temptation to perform web-research as procrastination. Set a time limit on research like this of about 10 minutes to make sure that you don't spend an hour reading *about* GitHub and have 5 minutes left to *actually use* GitHub).


## Your First Workflow With GitHub

When you are starting out, there are only 2 things I want you to be able to do with Git and GitHub:

- Create a repository on your computer and upload it to GitHub.

- Commit your changes and upload them to GitHub.

### How to create a local repository and upload it GitHub

In your Terminal (a.k.a shell), navigate to the folder containing your project. For our example, our preject folder will be name `myProject`, but this could be any folder in any directory.

`cd` into your project folder and type the following:

```bash
git init
```

This initializes the Git repository. This tells Git that we want to track all of the files inside this folder.

These instructions will only work if you have at least one file in the directory. If you don't have a single file, none of this will work and you will need to create a file before continuing. If you would like to, now might be a good time to create a `README.md` file for your project. This is a 


```bash
git add .
```

This adds all of the files inside the folder to **staging area**. This means that when you type `commit` in the next step, you will be committing the files you added to the staging area right now. The reason this adds all of the files is that `.` is a special symbol in Linux that refers to the present directory. You could have also added a single file by typing something like `git add myFile.txt`. But right now, we want to add **all** files in the current directory, so we're going to stick with the `.`

(*Sidenote: The `.` symbol is prounounced "dot"*)

```bash
git commit -am "initial commit"
```

This commits your staged files and adds a commit message (in this case, that message is 'initial commit'). 

Now you are ready to create an empty repository on GitHub, which is where we will push our code.

- Open your web-browser and login to your GitHub account.

- Click on the **Repositories** tab and click the green **New** button to add a new repository.

- Give your repository a name and an optional description.

- Leave the default settings (**Public** and don't check "**Initialize this repository with a README**") and click the green button to **Create a Repository**.

Now your empty repository exist on GitHub. In order to tell your local computer where to push your files to, copy the two lines of code from GitHub under the line that says: **Push an existing repository from the command line**:

The code will look something like the following, but will be customized for your username and the name of your repository:

```bash
git remote add origin https://github.com/andyroo2000/example.git
git push -u origin master
```

You want to copy each line one at a time, paste it into the terminal (making sure your are inside your project folder) and hit the enter key.

If all goes well, when you refresh GitHub in your browser, the code on your computer should now be viewable on GitHub.

## Your second workflow with Git

Now that you have created a local Git repository and a remote repository on GitHub, you should make a habit of commiting changes locally and pushing them to GitHub regularly.

Let's say that you've been working on your project and have just made a major change to your code, like adding an **about** page...

That would be a good time to commit your local changes using Git and then push them to GitHub. This will allow you to roll back your changes to this point at any time in the future.

`cd` into your project folder and type the following:

```bash
git add .
```

Again, this will add the files in the current directory to the staging area.

```bash
git commit -am "create about page"
```

This commits our changes with a descriptive commit message. This can be whatever you want, but it is a good practice to make it concise, descriptive, and in the present-tense (i.e. *create* instead of *created*).

```bash
git push
```

Since we defined our GitHub repository as the remote repository when we created it in our **First workflow with Github**, typing `git push` will push the code to GitHub.



