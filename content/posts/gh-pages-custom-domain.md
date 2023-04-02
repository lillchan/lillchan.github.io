---
title: "Custom Domain and Github Pages"
summary: "Using my own domain with Github pages."
date: 2023-04-02
tags: ["coding"]
---

Followed the official Github docs for [Managing a custom domain for your Github Pages site](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).

* added my custom domain in the repo settings
  * the dns check will fail for now, since the CNAME record hasn't been added
* edit the CNAME record for the `www` subdomain to point to my github pages site
* wait...
* the next day, confirmed that 'www.lillchan.com' was pointing to my github pages site
  * `dig www.lillchan.com`
