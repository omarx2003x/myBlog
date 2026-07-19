+++
date = '2026-07-08T15:20:15+02:00'
draft = false
title = 'how to make a blog'
description = 'how to make a blog website with Hugo'
+++
## Introduction

- This article explains the steps of  how to make your own blog website using [hugo](https://gohugo.io/) static site generator,
 To make a website, there is an overwhelming number of technologies and tools to choose from, but who doesn't like the free & easy option right ?.
- I chose Hugo for it’s simplicity and minimal learning curve , it serves it’s intended purpose to simplify the process of making and maintaining new static sites.
- Before we begin let me clarify what's exactly the difference between a [static and a dynamic website](https://www.geeksforgeeks.org/websites-apps/static-vs-dynamic-website/).

> Essentially a static website is a collection of web pages that are fixed (static), and they don't change according to a user or a database (if any), requiring minimal interaction between the server and client, thus resulting in more speed.

> Dynamic websites are the exact opposite.

> This blog is a static website.

{{< gallery >}}
<img src="static-vs-dynamic-websites.jpg" />
{{< /gallery >}}
 
---

## Requirements 
| tool | what's needed | 
|-------|:------:|
| - [Go language](https://go.dev/) | just have it installed on your computer |
| - [git](https://git-scm.com/) | for themes and deployment |
| - [linux](https://en.wikipedia.org/wiki/Linux) | you need a linux machine  | 
| - [markdown](https://markdownlivepreview.com/) | we gonna use markdown syntax | 
| - [html](https://en.wikipedia.org/wiki/HTML),[css](https://en.wikipedia.org/wiki/CSS),[js](https://en.wikipedia.org/wiki/JavaScript)| Optional , helps with debugging and control | 
| - [Hugo](https://gohugo.io/) | [what's Hugo?](#whatshugo) | 

- This might sound overwhelming at first but the previous tools either should just be installed or have a minimal learning curve. 
--- 

## What is Hugo ? {#whatshugo}
 - Hugo as we stated previously is a static site generator.
 - we utilize Hugo to simplify the process of making and maintaining static sites.
 - Hugo turns making blog sites as simple as writing a markdown file (literally).


{{< youtubeLite id="0RKpf3rK57I" label="Hugo" >}}


**want to learn more about Hugo ? Check**
- [documentation ](https://gohugo.io/documentation/)

- [how to make your own website with hugo](https://www.youtube.com/watch?v=hjD9jTi_DQ4)

- [basic Hugo tutorial](https://www.youtube.com/watch?v=qtIqKaDlqXo&list=PLLAZ4kZ9dFpOnyRlyS-liKL5ReHDcj4G3&index=1)
---


## Installing Hugo
 - installing Hugo is as simple as running one command, depending on your linux distro (or package manager).

{{< tabs >}}

    {{< tab label="apt" >}}
	```
		sudo apt  install hugo
	
    {{< /tab >}}

    {{< tab label="dnf" >}}
	```
		sudo dnf  install hugo
	
    {{< /tab >}}

    {{< tab label="Other package managers" md=false >}}
    {{< alert >}}See [documentation](https://gohugo.io/installation/).{{< /alert >}}
    {{< /tab >}}

{{< /tabs >}}

---
## Choose a theme
- it  always feels good to have overwhelming amount of [options](https://themes.gohugo.io/) (or does it?).
- let me tell you about my theme selection criteria. 
	1. documentation.

		a good theme must have a coherent &  concise documentation.
	2. support.

		having a decent user base makes debugging and problem solving much easier.
	3. usability.

		your theme has to be fully functional and be appealing to the user.
	4. customizability.

		your theme better be easily customizable to suite your preferences and needs.


{{< alert >}} make sure to check your selected theme's documentation before anything {{< /alert >}}

---

## Deployment

- essentially, Hugo converts your markdown content into html files to be viewed by the browser.
- the files are converted and placed in the `public` directory.
- deploying your website can be as simple as pushing the `public` folder into your github repo.
- but there is a better way to do this.
- we can instead push our project to github (execluding the `public` folder)
- then configure github to build your website on demand!.
- what? there is an even better way to it? 
- after pushing your project to github you can use a third party service to build your project and provide you a custom domain!.
- be sure to check your theme's documentation for more information.

---

## Final words

- throughout this article lots of decisions have been made.
- we chose use a static website, we chose hugo and markdown for generating our website, and we chose github and netlify for deployment.
- many things could have been done differently.
- but most importantly, we decided to make a website
- *why would you want to make your own website?*
- in our modern digital infrastructure owning a websites is a way to preserve your presence on the internet.
- having social media accounts may seem sufficient for you but owning your own digital space is beyond social media.
- making a website was an entertaining and an informative experience and i think you could give it a shot.
- have fun!.

---

> {{< typeit >}} No AI slop has been used in this article {{< /typeit >}}
