---
title: Software Developer
parent: Onboarding
nav_order: 2
---

# Onboarding: Software Developer

Hey SWEs! Glad you could make it :)

We have for you a few small challenges that shouldn't be too difficult to complete!

> Make sure to communicate on the #onboarding channel on Discord to get feedback!

First and foremost:

1. Create a Github [account](https://docs.github.com/en/github/getting-started-with-github/signing-up-for-a-new-github-account)
2. Send your Github username to Hrithik on Discord to be added to the SFL Github org
3. [Learn](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources) about Github
4. Set up [Git](https://docs.github.com/en/github/getting-started-with-github/set-up-git)

Now that you've gone over the basics, let's get our hands dirty! Here's your onboarding exercise:

## Some goals

Our goal is to:

-   Understand the Git workflow we're going to be implementing!
-   Deploy our own personal websites!

## What you need to do

First you're going to complete this Git workflow:

## Prerequisites

You will need to have Git installed before you proceed. If you do not have Git, follow [this link](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) to find the instructions that correspond to your operating system.

## Command line

A lot of work that we'll be doing will revolve heavily around the CLI (command line interface).

Don't be afraid if you haven't really gotten used to it - it's actually very intuitive once you get the hang of things.

Please begin by watching the CLI tutorial corresponding to your OS (even if you know some basics):

-   [Windows CLI tutorial](https://www.youtube.com/watch?v=MBBWVgE0ewk)
-   [macOS CLI tutorial](https://www.youtube.com/watch?v=aKRYQsKR46I)

> If you use any \*nix (excluding mac) OS I'm sure you know your way around a terminal. 🥇

## Git

**USE YOUR COMMAND LINE FOR THIS ONLY!**

1. Look at [https://github.com/Software-For-Love/obstacle-course/blob/master/swe-put-your-name-here.md](https://github.com/Software-For-Love/obstacle-course/blob/master/swe-put-your-name-here.md)

> You're going to be inserting your name here!

2. Clone the repository to your local machine. Open your command line and find the folder in which you would like to save this repository. Then, copy the following command:

```bash
git clone https://github.com/Software-For-Love/obstacle-course.git
```

3. Create a new branch. Enter the following commands line-by-line:

```bash
git pull origin master
git checkout -b yourname/purpose-of-branch (i.e. faiz/adding-name)
git branch
```

When you type the last command, you should see the name of the branch you just created! 4. Modify the file `swe-put-your-name-here.md` 5. Push to **your** branch!

```bash
git status
git add -A
// ^ use at your own risk
git commit -m "my message that follows the guidelines"
git push -u origin my-guideline-abiding-branch-nam
```

6. Open a Pull Request from your branch to the master!
    > Read this [https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)
7. Request review from [@Suri111200](https://github.com/Suri111200)!
    > Usually you will request a review from your SWE lead developer!
8. Await approval!
    > If there are any issues you'll have to refactor your work! We're all here to help with that so don't be afraid to make mistakes!
9. Once I have approved and merged your branch, you can delete it if you'd like.

Take a look at my Pull Request! [https://github.com/Software-For-Love/obstacle-course/pull/2](https://github.com/Software-For-Love/obstacle-course/pull/2)

Take a look at a Contribution Guide I wrote for an open source project - it might help you out:

-   [https://github.com/FaizChishtie/accessible-js/blob/master/CONTRIBUTING.md](https://github.com/FaizChishtie/accessible-js/blob/master/CONTRIBUTING.md)

Second you'll create and deploy a website!

## Website

### Node

We need to get used to working with node.js!

-   **Node.js Install: (Win/macOS)** [https://nodejs.org/en/download/](https://nodejs.org/en/download/)
    > We'll be using TypeScript (we're going to be using TypeScript since it removes a lot of ambiguity!)

Node can be hard to install/get used to - you're going to have to get comfortable using the command line!

You should be able to run `npm` in your command line after installation.

### Gatsby & Yarn

Once you've installed node on your machine, you're going to install Gatsby.js!

You're going to run this command in your command line: `npm install -g gatsby-cli`

> You should now be able to write `gatsby -h` to get the gatsby command line help menu!

We're also going to be using `yarn` as our dependency management tool rather than `npm` because it's cooler.

`npm install -g yarn`

### Template

After that you're going to download this template through your command line via:

`gatsby new gatsby-starter-default https://github.com/gatsbyjs/gatsby-starter-default`

You should see a new folder called `gatsby-starter-default`.

`cd` into it and run `gatsby develop` to run the website on your localhost!

Tinker around with it a bit! (check under /src for js files).

### Deploying

After fiddling around with the template! You're going to deploy it using Netlify!

Upload your code to a git repo!

Follow the instructions on netlify to connect and deploy your application. Make sure to ask for help if you need any!

Check [https://sesanotes.netlify.app/](https://sesanotes.netlify.app/) to see a site I developed with Gatsby and deployed with Netlify!

### Summary

**MAKE SURE TO ASK FOR HELP IF YOU NEED IT!**

So you're going to:

1. Add your name the proper way to the file in Git! (We're going to get merge conflicts based on the order we submit so get ready to deal with those!)
2. Install node/gatsby/yarn
3. Create a Netlify account and deploy your own website
4. Submit your site URL in the #onboarding channel on Discord
5. Give feedback and help to others (I'll be here to help out!)

This should be completed within _7 days_ of you being assigned this task!

Good luck!
