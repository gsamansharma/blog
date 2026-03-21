---
title: "Building an Interactive Portfolio with Next.js"
description: "A breakdown of how I built my portfolio—from a terminal-style experiment to a fully interactive OS-inspired website—along with the challenges, design decisions, and lessons learned along the way."
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

How I developed my portfolio


I always wanted to have a portfolio website which would be interesting not boring

Being a linux entusiast, I decided to build a terminal-based portfolio that would look cool.

But there were problems, one of them was making it responsive for both desktop, mobile, tablet, etc

The second problem was usability. It was difficult to navigate. Imagine using commands for navigation, only terminal enthusiasts would find that interesting, which meant it wouldnt appeal to a broader audience.

So, here comes the second version, I decided to implement an OS styled portfolio.

Basic plan, it would have my projects, research articles, resume, social profiles, skills and the terminal website you remember. This version was complete and built entirely in vanilla JavaScript. 

But again, there was a problem, I couldnt resuse the components easily


So, here comes the next version(pun intended)

I chose next because “lets be honest” who doesn’t want their name to show up on Google when someone searches for them?

I wanted server side rendering so crawlers could properly see my website, index and rank it.

So, built this, asked my friends to review it

They liked the concept but didn’t like the wallpaper.
They said it was distracting.

So, the next challenge was to find a very minimal wallpaper that didn’t steal the show, took help from gemini.


But even after that, the site still felt incomplete.



Now, I have to find more things to make it good looking.

Another challenge was handling layouts.
Having a single responsive design for both desktop and mobile was difficult. It wasn’t just about adjusting widths.

So instead of depending on media query, I created a dedicated desktop layout(for larger screens) and the mobile one remains as it is


Then I added:
Windows for projects and projects and skills (desktop)
Modals for mobile

Next challenge theming

Dark mode is popular, but you can’t ignore users who prefer light mode.
So I implemented both.




Now, it was ready,

I started sharing it publicly across platforms, but didn’t get much attention.  

Then randomly, I shared it on Reddit without any expectations.
And it blew up.
It got a lot of comments and likes, and the post stayed in the top 10 for that month.


That’s when I thought why not make a portfolio builder, so others could enter their data, make profiles and decided the Saas name to be showmy.page.

What Next?

This is just the beginning.
A detailed blog on ShowMyPage is coming soon.
---
