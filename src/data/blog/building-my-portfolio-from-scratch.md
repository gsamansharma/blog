---
title: "Building an Interactive Portfolio with Next.js"
description: "A breakdown of how I built my portfolio—from a terminal-style experiment to a fully interactive OS-inspired website—along with the challenges, design decisions, and lessons learned along the way."
pubDatetime: 2099-03-23T00:00:00Z
slug: building-my-portfolio-from-scratch
featured: false
draft: true
tags:
  - portfolio
  - side-project
  - showmypage
  - react
  - nextjs
---

## The Idea: A Portfolio That Isn’t Boring


I always wanted a portfolio website that felt different—something interactive and fun instead of the usual static pages. I wanted it to reflect my personality and interests.

---

## Version 1: Terminal-Based Portfolio

Being a linux entusiast, I decided to build a terminal-based portfolio that would look cool.

### Challenges:

But there were problems, one of them was making it responsive for both desktop, mobile, tablet, etc

The second problem was usability. It was difficult to navigate. Imagine using commands for navigation, only terminal enthusiasts would find that interesting, which meant it wouldnt appeal to a broader audience.

---

## Version 2: OS-Styled Portfolio

So, here comes the second version, I decided to implement an OS styled portfolio.

### Features:

Basic plan, it would have my projects, research articles, resume, social profiles, skills and the terminal website you remember. This version was complete and built entirely in vanilla JavaScript. 

### Problem:

But again, there was a problem, I couldnt resuse the components easily

---

## Version 3: Moving to Next.js

So, here comes the next version(pun intended)

### Why Next.js?

I chose next because “lets be honest” who doesn’t want their name to show up on Google when someone searches for them?

I wanted server side rendering so crawlers could properly see my website, index and rank it.

---

## Design Iterations: Feedback & Improvements

So, built this, asked my friends to review it

### Issues Identified:

They liked the concept but didn’t like the wallpaper.
They said it was distracting.

### Fixes:

So, the next challenge was to find a very minimal wallpaper that didn’t steal the show, took help from gemini.


But even after that, the site still felt incomplete.



Now, I have to find more things to make it good looking.

Another challenge was handling layouts.
Having a single responsive design for both desktop and mobile was difficult. It wasn’t just about adjusting widths.

---

## Responsive Design Challenges

So instead of depending on media query, I created a dedicated desktop layout(for larger screens) and the mobile one remains as it is

### Additions:

Then I added:
Windows for projects and projects and skills (desktop)
Modals for mobile

---

## Supporting Both Light & Dark Modes

Dark mode is popular, but you can’t ignore users who prefer light mode.
So I implemented both.

---

##  Launch & Initial Response

Now, it was ready,

I started sharing it publicly across platforms, but didn’t get much attention.  

---

## Breakthrough on Reddit

Then randomly, I shared it on Reddit without any expectations.
And it blew up.
It got a lot of comments and likes, and the post stayed in the top 10 for that month.

---

## 💡 The Next Idea: SaaS Product

That’s when I thought why not make a portfolio builder, so others could enter their data, make profiles and decided the Saas name to be showmy.page.

---

## What Next?

This is just the beginning.
A detailed blog on ShowMyPage is coming soon.



---
