---
title: "New Hugo Site Setup"
summary: "Steps to setup initial Hugo site"
date: 2023-04-01
tags: ["coding"]
---

I keep meaning to publish something to this domain, but never quite finishing anything, so here's my attempt at getting some bare minium pushed. 🤪

Setup steps:

* create new github repo 'lillchan.github.io'
* git clone repo
* new hugo skeleton: `cd lillchan.github.io && hugo new site . --force -f yml`
  * yaml config recommended by papermod theme
* [install papermod theme](https://github.com/adityatelange/hugo-PaperMod/wiki/Installation)
* edit root config file
  * [papermod features](https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-features/)
  * [papermod config params](https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-variables/)
  * [papermod sample config](https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-installation/#sample-configyml)
* publish post: `hugo new posts/my-first-post.md`
* add [archives page](https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-features/#archives-layout)
* add [search page](https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-features/#search-page)
* start server + publish drafts: `hugo server --buildDrafts`
* setup [github pages with hugo](https://gohugo.io/hosting-and-deployment/hosting-on-github/)
  * needed to convert the git origin remote on this repo from http to ssh
* commit and push hugo site to repo
