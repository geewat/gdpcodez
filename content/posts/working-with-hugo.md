---
title: 'Choosing Hugo Over WordPress: Insights from a Long-Time WordPress User'
date: 2023-12-11T21:22:19Z
draft: false
image: img/hugo-hero-final.jpg
tags: ["Hugo","blogging", "personal"]
categories: ["Personal"]
---

In this post, I'd like to take a moment to talk about my decision to use Hugo as a blogging platform over WordPress despite my years of experience developing sites with WordPress. As a word of note: this is not a tutorial on how to spin up and manage a Hugo website. I might do a mini tutorial for my own benefit down the line, but for the purposes of this post, the tone is purely conversational.

## My Reasons for Blogging 

In fact, I'd like to take a step back from that and explain why I even started this blog. Not long ago, I decided to start digging more into the world of modern web development. [You can read more on that here.](https://gdpcodez.co.uk/posts/my-journey-to-modern-web-development/) I worked through some lessons on CSS fairly quickly but outside of CSS Grid, there wasn't too much for me to take note of. CSS Grid is now something that I've started to utilise more and more in my day to day work. Long gone are the days of floating divs and using Javascript to handle equal column heights.

After working through part 1 of a fundamentals course on JavaScript, I picked up enough nuggets of information that I felt it was worth taking notes for my own benefit. Initially, I dropped these into Notion with the intention of going back and writing up a summary for myself just as a way to recap the information. It was at that point that I figured it might actually be interesting to document this journey in a blog. 

I also feel strongly that being able to take things and explain them back in your own words is a great way to help yourself understand new things you are learning. So really, I could both document my journey and reinforce my learning of the material for that journey.

## Deciding Against WordPress

When I decided to start this blog, my initial reaction was to quickly spin up a WordPress installation, grab a free blogging theme, and go to town. Then I remembered that one of the core reasons for me doing all of this is to learn new things! 

As such, I immediately took WordPress off the table. 

I had an awareness of static site generators but never had a reason to use them. This was an opportunity to hit the ground running with something brand new. I figured a modern static site generator might also force my hand to start using technologies like Git, GitHub, and automated deployment, which are all things I have had some exposure to in the past but had got out of the way of using.

After some quick-ish research, I settled on Hugo as my platform of choice based on a combination of reviews and perceived ease of use.

The funny thing is I ended up spending the guts of 2 weeks learning how to set up a site with Hugo, which actually derailed my Javascript learning slightly. That being said, a lot of learning still happened to get this blog up and running. I ended up having to create a GitHub account for the first time (shock horror for this developer) along with a Netlify account for hosting the site. The Hugo workflow, coupled with the double team of GitHub and Netlify, allows me to work locally, push to GitHub, and deploy automatically to Netlify. Purchasing the domain name GDPCodez.co.uk (GDP stands for Gareth David Peter, by the way - my full name) rounded everything off, and now I have what I feel is a tidy little process for running my blog going forward.

## Is Hugo Better Than WordPress?

I have to be honest and say that while it's cool to spin up a local host, make changes, commit to version control, and deploy to a live server, this is a user experience only intended for developers. Now that I've spent a bit of time using this workflow, I do admit to liking the 'cool factor' a little more than I should. 

Where things fall down a bit is in the actual creation of content once you get going. With Hugo, you create markdown files and write your posts that way. While Markdown is handy in that you can format your text using markdown tags without having to use the mouse, when you are dealing with images, it gets a bit messy. Images need to be saved locally in a particular folder and then their filename dropped into the markdown file. It's fiddly, more than anything else. 

That's not to say it's all bad regarding Hugo. Far from it, in fact. Not having to log into the backend of WordPress and wait for things to load up is nice, and just being able to use the command line to create content is convenient and handy. Also, the local server experience is nice and lightweight. These days, I don't work locally as much as I used to (there are reasons, and that might be the topic of a post for another day), but when I did, there was a bit of effort in spinning up a local server to run a WordPress site. With Hugo, there is a built-in command that launches a local server quickly and allows changes to be seen in real-time without having to install any extra modules outside of Hugo.

Another undeniable advantage to Hugo over WordPress is the security and the lack of updates. WordPress has a large target on its back, and as such, WordPress and plugin developers need to be fighting this on an ongoing basis. Hugo has no database to exploit, and the end product is a website powered by static files, which makes it significantly more secure. With fewer third-party software running things and no dynamic components, I feel that the trade-offs work in favor of Hugo for my own particular needs.

## So In Conclusion...

I am happy to keep using Hugo as a blogging platform for myself. I am not sure if I will ever go down the path of learning how to code themes for it or of using it to offer static websites to clients. Fundamentally, WordPress still offers a lot and allows fairly complex websites to be spun up quite quickly. I do still get frustrated by the overheads needed to run a WordPress site from a maintenance point of view, and potentially there are other options for me to explore down the line (potentially using Hugo as the frontend for a headless CMS), but for now, WordPress stays, and Hugo remains my personal blogging platform of choice.
