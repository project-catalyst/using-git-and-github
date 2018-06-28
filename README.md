# Using Git and GitHub

Note: This document is a work in progress. If you find yourself here and have suggestions for how to improve it or questions contact me on twitter [@dwesty17](https://twitter.com/dwesty17) or by email at j.dylan.westerhold@gmail.com. I'll do my best to get back to you.

Reading Time: **? minutes**

## Lessons
1. [Using a Command Line Interface](https://github.com/project-catalyst/using-a-cli) (? minutes)
1. [Installing Homebrew](https://github.com/project-catalyst/installing-homebrew) (? minutes)
1. [Running A JavaScript Program](https://github.com/project-catalyst/running-a-javascript-program) (? minutes)
1. **Using Git and GitHub**
1. [Intro to JavaScript](https://github.com/project-catalyst/overview) (? minutes)
1. [JavaScript Lesson 1: Variables and Data Types](https://github.com/project-catalyst/overview) (? minutes)
1. [JavaScript Lesson 2: Functions](https://github.com/project-catalyst/overview) (? minutes)
1. [JavaScript Lesson 3: Conditional Statements and Loops](https://github.com/project-catalyst/overview) (? minutes)
1. [Intro to React](https://github.com/project-catalyst/overview) (? minutes)

## Overview

### git

git is a software created by Linus Torvalds, who also created the Linux operating system. It is described as source code management (SCM), and it allows a developer to work on different versions, or branches, or a project. These branches are created from each other and can be merged back into each other. 

This is useful for many reasons, one being that you may decide after doing some work that you either want to get rid of it or switch your focus to some other task without completeing what you were working on. Going back through your code base and back tracking on every change you made is time consuming and prone to mistakes. It's much easier to delete or leave the branch you were working on and create a new one.

SCM is incredibly useful, though, for teams. Keep in mind that the following are the most common proactices I'm familiar with, but are by no means standards for how to use git. Every team has their own git branching strategies, and some use alternative SCMs

Often the main branch in a project is called `master`, and it's common on a software team that the `master` branch is the version of the project that contains all the production code. So, when `master` gets updated so does their software, which may happen automatically or may require a manual step.

It's also common to have another branch named something like `develop`, which contains the version of the software with mostly completed featured for the next software release. So, merging `develop` into `master` begins the release process.

For every new feature a team works on they'll create a branch or set of branches to user until they consider their work production ready. At this point they will merge their feature branches into `develop`.

This type of branching strategy is very common and may be reffered to as feature branching.

### GitHub

GitHub is a company that's created a web product around the features of the git software. It provides a UI wrapper around some of the common git commands, but more importantly provides a centralized repository to store your git project. So, a developer can work locally on whichever branches they create and then push their code up to a remote version of that branch that other members of their team have access to. This is crucially important for a team of people to be able to work on a porject together.

## Using git

## Next Lesson