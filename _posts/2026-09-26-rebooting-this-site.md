---
title: Rebooting this site
layout: post
description: Notes on modernizing the build and finally putting real content here.
---

This site sat untouched for a while — default Jekyll boilerplate, a lone "Um." post, and a GitHub Pages build pinned to Jekyll 3.9.3 via the legacy `github-pages` gem. Time for a refresh.

What changed:

- Moved the build off the legacy GitHub Pages pipeline and onto a GitHub Actions workflow, so the site now builds on current Jekyll (4.x) instead of whatever version the `github-pages` gem happens to bundle.
- Dropped the `github-pages` gem entirely in favor of explicit dependencies (`jekyll`, `jekyll-remote-theme`, `jekyll-feed`, `jekyll-seo-tag`).
- Wired up the [monophase](https://github.com/paulmcarrier/monophase) theme properly — navigation and social links now live in `_data/` instead of being hardcoded.
- Replaced the "Under Construction" homepage and default About page with actual content.

Plan going forward is to use this for project writeups and the occasional life update, instead of letting it sit idle.
