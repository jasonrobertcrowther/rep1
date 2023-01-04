---
layout:     post
date: 2022-11-20
#description: "the thought process"
#featured_image: "https://source.unsplash.com/aWrkBDjpxQ8"
title: "Getting started - Part 1 - the thought process"
tags:
    - Setup
    - Website
    - Jamstack
    - Cloudflare
    - Static
author: "Dan"
showthedate: false
weight: 2

---

I thought it was time to setup some form of central repository or portfolio of my work when I started visiting university open days and wanted to be able to showcase my work so far. This article aims to outline the initial steps take to get off the gound.

Currently the content I have created exists in a number of places. Some exists on YouTube in private channels and some exists at College in private server locations. What I want to be able to do is show these videos and the ideas behind them to the viewer

While there are lots of content management solutions out there for websites being a "poor student" I decided that challenge number 1 should be how to create a website as cheaply as possible. Challenge number 2 would be to take the "empty webspace" and create a theme or template so I could easily upload my content. Challenge number 3 would be to add layers of security to ensure I could have non public 
access if ever required

So in reality - lots of challenges! The first thing to do is find some form of website hosting. That may be a platform that has prebuilt templates and themes or simple empty space that I then need to work more on creating the content and look and feel. While there are a number of "free" platforms out there I didn't want their identity to be part of my portfolio so I decided I would need to start from a blank sheet - which feels more in line with the whole "creativity" idea which is fundamental to what I do.

While looking for something that matched this idea and also with the idea of being cheap or certainly affordable and also secure (I know - I want everything for nothing) I stumbled upon Cloudflare (https://www.cloudflare.com). This is a essentially a Content Delivery Network (CDN) but their tagline "Cloudflare is a global network designed to make everything you connect to the Internet secure, private, fast, and reliable." works for me.

More importantly there is a free fier that allows me to get started at no cost and see whether it suits my requirements.

I decided at this point the primary aim was to build the framework so I could add my content and then add a domain name later

After digging a bit deeper and without boring the reader with the details I found that Cloudflare Pages is a Jamstack platform (https://jamstack.org/what-is-jamstack/ ) that can be used to develop websites. There are two key concepts here:

+ *Jamstack is an architecture designed to make the web faster, more secure, and easier to scale. It builds on many of the tools and workflows which developers love, and which bring maximum productivity.*

+ *With Jamstack, the entire front end is prebuilt into highly optimized static pages and assets during a build process. This process of pre-rendering results in sites which can be served directly from a CDN,
reducing the cost, complexity and risk, of dynamic servers as critical infrastructure.*
 
My thinking here is that with video content becoming more and more dynamic and being a modern technology then a number of key points are met with this approach - specifically **reducing the cost** - **reducing the risk** and **a worldwide Content Delivery Network**

If I can deploy my website on Cloudflare with the free tier then this gives me the start I need

One of the concepts I noticed was that what was being repeatedly mentioned was **static websites** - surely this conflicts with the idea of me being able to regulraly upload content - ie - more dynamic. However after reading a bit more deeply it became evident that actually my content is the videos that I create. Once created I just want to showcase them - so actually a fairly static website would suit my purposes as long as I could add content as I went along - almost more of a **blog** type website. 

Wow do I create this website. The Cloudflare documentation provided the answer to this - a Jamstack based tool would allow me to create a website framework and then then just add my content as I went along. So what tool to use - it turns out there are many - all with great names like Gatsby, Hugo, Jekyll and many more. Since I know none of them a google search was my friend and Hugo was selected based on the following:

+ *Hugo is a static site generator written in Go. It is optimized for speed, easy use and configurability. Hugo takes a directory with content and templates and renders them into a full html website.*

So - Cloudflare plus Hugo plus my content - thats going to be my platform - all I now need to do is work out how to do it!!!


