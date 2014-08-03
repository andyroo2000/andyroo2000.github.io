---
layout: post
title:  "Intro to Git"
date:   2014-08-01 21:32:46
categories: musings
---

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



