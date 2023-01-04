---
layout:     post
date: 2022-11-19
#description: "the practicalities"
#featured_image: "https://source.unsplash.com/aWrkBDjpxQ8"
title: "Getting started - Part 2 - the practicalities"
tags:
    - Setup
    - Website
    - Jamstack
    - Cloudflare
    - Static
author: "Dan"
showthedate: false
weight: 3
series : ["Infra"]
---

After a bit of a crash course in googling how to do things its time to join all the dots...

Hugo
Installing Hugo was fairly painless and it has some great features like the ability to preview my changes on the fly.

I then found a simple theme from the Hugo themes library https://jamstackthemes.dev/theme/hugo-theme-cleanwhite/ which should allow me to use a simple blog structure and menu items

I did some basic customisation of the theme so Hugo is ready to go

The actual website pages are delivered to Hugo using simple text files with markdown https://en.wikipedia.org/wiki/Markdown for formatting so the next stage was to create the simple page structure by editing a bunch of text files and dropping them into the hugo file structure.

Every change or update can be seen live by the preview functionality so it was quick to get up and running.

A few tweeks later with the configuration and I had the structure and basic content.

Once happy it was a simple process to export the full website to a bunch of html files that just need uploading to my hosting platform (Cloudflare)

A few minutes later a Cloudflare account was setup and I was ready to go. Cloudflare requires me to have my own domain name so I used one I already have but can change this later

To maintain change control and keep on top of things GitHub is the tool of choice. This enables me to maintain a repository of my files and a history of changes. GitHub integrates natively to Cloudflare!!

At this point it was just a matter of telling Cloudflare to create a Cloudflare Pages Project and linking it with my repository. Now in theory updates are easy.. run hugo->make changes to website->export website to GitHub repository->tell GitHub to upload changes.

The default Cloudflare Pages website looks good and now all I need to do is link it to my domain. This again was simple enough and Cloudflare handles all the DNS settings and security

Website done and working and linked to my domain - now all I need to do is get all the content uploaded
