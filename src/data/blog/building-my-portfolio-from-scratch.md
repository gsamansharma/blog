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

<figure style="margin: 2rem 0; text-align: center;">
  <video autoplay loop muted playsinline style="width: 100%; border-radius: 8px;">
    <source src="/assets/building-my-portfolio-from-scratch/terminal-portfolio-preview.webm" type="video/webm">
    Your browser does not support the video tag.
  </video>
  <figcaption style="font-size: 0.875rem; color: var(--color-text-base); opacity: 0.8; margin-top: 0.75rem;">Terminal-Based Portfolio Interface (Version 1)</figcaption>
</figure>

### Challenges:

* Making it responsive for both desktop, mobile, tablet, etc.
* Navigation was difficult for non-technical users.
* Commands for navigation only appealed to terminal enthusiasts.

---

## Version 2: OS-Styled Portfolio

So, here comes the second version, I decided to implement an OS styled portfolio.

<figure style="margin: 2rem 0; text-align: center;">
  <video autoplay loop muted playsinline style="width: 100%; max-width: 300px; border-radius: 8px; margin: 0 auto; display: block;">
    <source src="/assets/building-my-portfolio-from-scratch/mobile-os-portfolio.webm" type="video/webm">
    Your browser does not support the video tag.
  </video>
  <figcaption style="font-size: 0.875rem; color: var(--color-text-base); opacity: 0.8; margin-top: 0.75rem;">OS-Styled Mobile Portfolio Layout (Version 2)</figcaption>
</figure>

### Features:

* Includes projects, research articles, resume, and social profiles.
* Integrated the original terminal website as a feature.
* Built entirely in vanilla JavaScript.

### Problem:

* Components weren’t reusable, making it hard to scale or maintain.

---

## Version 3: Moving to Next.js

So, here comes the next version(pun intended). I chose Next.js for a few key reasons:

### Why Next.js?

* **SEO Optimization**: Server-side rendering allows crawlers to properly index and rank the site.
* **Component Reusability**: Makes the codebase much more maintainable.
* **Performance**: Faster page loads and better developer experience.

---

## Design Iterations: Feedback & Improvements

So, built this, asked my friends to review it.

### Issues Identified:

* Wallpaper was distracting.
* Overall design felt a bit incomplete.
* Needed cleaner UI and better visual hierarchy.

### Fixes:

* Switched to a minimal wallpaper (with help from Gemini).
* Focused on making it look good and handle different screen sizes.

---

## Responsive Design Challenges

So instead of depending on media query, I created a dedicated desktop layout (for larger screens) and the mobile one remains as it is.

### Additions:

* Window-based UI for projects and skills on desktop.
* Modals for the mobile experience.

---

## Supporting Both Light & Dark Modes

Dark mode is popular, but you can’t ignore users who prefer light mode. So I implemented both, ensuring a consistent design across both themes.

---

##  Launch & Initial Response

Now, it was ready. I started sharing it publicly across platforms, but didn’t get much attention initially.  

---

## Breakthrough on Reddit

Then randomly, I shared it on Reddit without any expectations. And it blew up:

<figure style="margin: 2rem 0; text-align: center;">
  <img src="/assets/building-my-portfolio-from-scratch/reddit-post.webp" alt="Reddit Post Success" style="width: 100%; border-radius: 8px;">
  <figcaption style="font-size: 0.875rem; color: var(--color-text-base); opacity: 0.8; margin-top: 0.75rem;">Reddit post that reached the top 10 of the month.</figcaption>
</figure>

* The post reached the **top 10 of the month**.
* It received a lot of comments, feedback, and appreciation.

---

## 💡 The Next Idea: SaaS Product

That’s when I thought why not make a portfolio builder, so others could enter their data, make profiles and decided the Saas name to be showmy.page.

---

## What Next?

This is just the beginning.
A detailed blog on ShowMyPage is coming soon.



---
