---
layout: post
title: Creating a Static Website with Jekyll Pages and GitHub
author: Elizabeth Jellison
categories: blog
tags: documentation,
image: photos/work1.jpg
---

Starting something new is hard. You feel stupid and dumb, and the supposedly simplest tutorials are confusing no matter how many times you read them. That's how I felt learning GitHub and Jekyll, and making the site you are now on.

Tutorials are often frustrating. They are either too wordy and your eyes glaze over, or they are too vague. I tend to ere on the side of too wordy, as you might be able to tell, because as a new user, the worst thing for me is only getting most of the information. How many tutorials do I have to go through to get all the information I need? It's so time consuming, not to mention frustrating.

People who have been using the tools they write about forever forget what it's like to be a beginner. What is obvious to them is probably not obvious to you or me, unless you already have the vocabulary and background knowledge. I didn't, so it was a bit of a rough process for me. I am hoping, with this tutorial, I can prevent that for you.

But before I get into the tutorial, there are some concepts I want to go over that if you understand, make creating your new page a whole lot easier. They were the questions I had when I started!



### What is Jekyll?

Jekyll is a *static site generator*. It is an offshoot of GitHub which hosts and generates static sites for the users of GitHub Pages.

To understand what a static site generator is, first it helps to know what a *dynamic site* is.

Dynamic sites are what most people are used to when they go on the internet. When you go to a webpage, the *client* (your computer) makes a request to the *server* (the website) for content, which in turn queries its own *database* for that information. The content is sent back to the server which then loads it into the proper format, and sends it back to the client.

All of that happens the moment you click on a link or go visit a site. To the user the speed is usually instantaneous, assuming you have high speed internet access. In the world of the internet, its actually quite slow. And expensive.

But what if you are maintaining a blog? The content is only updated when you update it, so why do you need to go through all that to get some information that is pretty much...static?  

Exactly.  

Static sites are just that. Static. The content is made up of plain-text files, also called flat files, usually written in Markdown, and hosted on a server, it's structure already formatted by the code used to build the site. Instead of the content being loaded when you visit the site, queries made to databases, and all the other stuff it takes to run a dynamic site, the content has already been updated and requires only one request from the client to the server. It's fast and takes less effort.

### Why should it matter to me?

Cost, mostly. Dynamic sites take a lot of different parts to run, and the more users it has, the more complex and expensive it becomes. Database contact, proxy servers, and load balancing are just a few of the things that are required for dynamic websites like, Facebook to run.

How do they keep it free and make money?

Well, in the famous words of CEO Mark Zuckerberg:

![]({{ site.github.url }}/assets/img/photos/screenshots/zuckerberg.gif)

"And I like ads!" said no one ever...

What make static sites an awesome alternative, is that they are cheaper to run and require less space and maintenance. They require a host and a static site generator, and it takes only one server request from the client to the server to retrieve content. Other advantages are version control and the ease of writing in plain text without the need to know any code.

Jekyll isn't the only static site generator, but it is owned by GitHub, which provides a unique service, eliminating the need for another service to host your content. GitHub hosts the content for free, leaving more money for you to spend on something else.

Like beer.    

![]({{ site.github.url }}/assets/img/photos/screenshots/wahoo.gif)


So if you don't already have a GitHub account, go now and sign up for one!

### A few things before we get started...

There are two types of GitHub Pages, but for this tutorial I will be focusing on how to create a user page.

Your user page is the page you create under your GitHub account name. It is created under the master branch, and only the master branch.
The address will be `http(s)://<username>.github.io`, with `username` being replaced with your GitHub account name.

 * For example, you are reading this on my GitHub User page, `kanyewesternfront.github.io` with my domain name functioning as my address.

### Creating a User Page the Easy Way

Let's get started!

1. Login to your GitHub account.

2. Click **New Repository**

![]({{ site.github.url }}/assets/img/photos/screenshots/create-new-repo.png)

3. Name the repository using the following format: `<username>.github.io`, replacing `username` with your GitHub account name.

  - NOTE: You **MUST** name your user page with the same name as your GitHub account or it will not work!!

![]({{ site.github.url }}/assets/img/photos/screenshots/new-repo-name.png)

(I did not add the "o" to the end of the name because that repository already exists, but you need to!)

4. Select **Public**

5. Check **Initialize this repository...**

6. Click **Create Repository**.

7. Click **Settings** and scroll down to GitHub Pages.

![]({{ site.github.url }}/assets/img/photos/screenshots/create-page.png)

8. Click on **none** and select the master branch.

![]({{ site.github.url }}/assets/img/photos/screenshots/select-master.png)

9. Click **Save**.

10. Click **Choose a Theme** and select which theme you want.

![]({{ site.github.url }}/assets/img/photos/screenshots/select-theme.png)

11. Click **Select Theme**.

And voila! Your GitHub user page is ready to edit and make your own! You can visit the page by typing your address into the search bar.

This is a very simple one page site, and the README file is where you will insert and edit the content for your page.
Make sure to read through the instructions contained in the README file before you edit them out. There is good information on how to use Markdown, how to edit, and how to change your theme.

Good luck!
