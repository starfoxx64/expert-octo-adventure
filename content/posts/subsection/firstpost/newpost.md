---
title: Inception Using Hugo
seo_title: Inception Using Hugo
summary: Building this site using Hugo showcasing basic Markdown syntax and formatting for HTML elements.
description: Building this site using Hugo showcasing basic Markdown syntax and formatting for HTML elements.
slug: Hugo Inception
author: Matt Fox

draft: false
date: 2023-07-21T15:15:26-05:00
lastmod: 2023-07-21T15:15:26-05:00
expiryDate: 
publishDate: 

feature_image: 
feature_image_alt: 

categories:
  - Web Development
tags:
  - Markdown
  - HTML

toc: false
related: false
social_share: true
newsletter: false
disable_comments: true
---

My goal with this site is to visualy demonstrate my skills and abilities as I progress through my learning journey. I wished to create a professional and visually appealing website without diving into the complexities of web development. In my research I stumbled uppon Hugo. In this blog post, I will share my journey of creating my website using Hugo.

<br>
<br>
<br>

## Step 1: Setting Up the Project

To get started, I installed Hugo on my computer by following the instructions on the [Hugo website](https://gohugo.io/getting-started/installing/). Once I had Hugo installed, it was time to create a new site. I opened my terminal and ran the following command:

```bash 
hugo new site foxden
```

"my-website" is the name I chose for my project, and Hugo created a new directory with that name to store all my website files.
<br>
<br>
<br>

## Step 2: Picking the Theme

I knew I wanted a visually appealing website, so I explored the Hugo Themes website to find the perfect theme for my site. After browsing through several options, I came across the theme "BlogRa." It had a clean and modern design that suited my tastes.

To install the theme, I used Git and the following commands in my terminal:
```bash 
cd foxden
git init
git submodule add https://github.com/wjh18/hugo-liftoff.git themes/hugo-liftoff
```
<br>
<br>
<br>

## Step 3: Creating Content

My website wouldn't be complete without content, so I started creating this very post you are reading right now. Hugo uses Markdown for content creation, and it's incredibly straightforward. I ran the following command in my terminal:

```bash
hugo new --kind post-bundle posts/subsection/fistpost/newpost.md
```
Hugo generated a new Markdown file for my first blog post, and I started writing using Markdown syntax. Writing in Markdown was completely new to me so I needed to frequently look up the syntax for headings, line breaks, etc. After a bit of time on the struggle bus, I think that I mostly got the hang of it.
<br>
<br>
<br>

## Step 4: Building the Website

When everything was in place, it was time to see my website come to life. I ran the following command to build my site:
```bash
hugo serve
```
This buit the website and hosted it on my local machine. I was able to view the site by visiting loacalhost:1313 in my browser. From there, I was able to continue to edit the post and see the changes in real time in my browser. Now I will be able to document my progress in my IT journey as I keep this site updated with projects I am working on. I will eventually publish this on the internet for any interested parties to see.
