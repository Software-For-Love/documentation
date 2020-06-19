---
layout: default
title: Coding Conventions
has_children: true
nav_order: 3
---

# Coding Conventions

## Development Practices 

Here’s a quick guideline for how we should be developing: 

* Test Driven Development (TDD):  
  * All public exported functions should have their own tests! 
  * Ideally, we should think of the tests before we begin even writing our exported functions. 
  * Private functions don’t necessarily need to be tested but better safe than sorry! 
* Git: 
  * We’re using GitHub for SCM so make sure you know how to create a PR and review code 
  * Pull Requests: 
    * Assign many people on your PRs to get the most code review possible 
    * Keep PRs small to avoid having huge amounts of code to be reviewed, split features up into multiple different tasks that can be tracked so if we break the code, we can revert easily 
    * Merge only your code in your PRs – avoid pulling from other branches and then creating PRs – gets messy 
    * Tests for each PR will be required so we can make sure our code works 
  * Make sure your branch names describe what functionality you’re implementing so we can track changes easily 
  * Travis (CI) will test your build and run the according tests so if that doesn’t pass, you’ll have to figure out why 
* General Practice: 
  * Don’t modify another person's code without asking 
  * If you don’t know something, ask people because sometimes that’s much faster than googling it 
  * Propose new ideas if you have any 
  * We must have some great documentation to accompany our module. Please document your functions. 