+++
title = "Why I chose HUGO to build my blog."
date = 2025-01-07
description = "TLDR: I don't want to type in raw HTML for hours on end."
+++

TLDR: I didn't want to type in raw HTML for hours on end. I originally attempted this and wanted to pull my hair out. After discussing with a friend of mine, they told me about HUGO. I didn't choose the HUGO life — it chose ME.

# The Beginning: departmentofwarfare.org

For a while now, I've wanted to begin my infosec blog but have had no clue where to start. For a while, I figured I'd go with the traditional website setup: Linux, Apache, MySQL, PHP (classic LAMP), as I do happen to have some experience with it at a previous job at my old community college. In addition, I found myself stuck on how I wanted to host my site. Did I want to pay hosting fees and host it remotely? Did I want to host it on my R720? Because of how I think, I ended up in task paralysis. It wasn't until I found the domain name "departmentofwarfare."

You might ask, why did the domain name snowball your blog creation, Justis? To be honest, it was for the LOLs. At the time, I was searching random things on Namecheap in anticipation of finding something cool. (Yes, I tried searching for my own name, but Justis.com is taken by a lawyer AI.) In my search, it just so happened that the US president began renaming the Department of Defense to an unofficial name of Department of War. In a golden moment, I decided to search for "departmentofwarfare.org."

I found this to be a grand opportunity as the name change for a government entity would cause some confusion somewhere in D.C. Plus, sounding out the wording "Department of War" vs "Department of Warfare" makes it easy to typo squat. Finally, the .org TLD gives the link an air of legitimacy, making it the perfect infosec blog domain.

# Creating the Blog: LAMP Approach

Once purchased, I waited till my winter break as I was busy with finals at the time. Once the break came around, I began developing the website and got somewhat far. Granted, what I wanted was a bit overkill for just a blog that a handful of folk would see. I'm talking a user-unique QOTD pulled from a DB in MySQL, unique site structure where everything is centered with the header containing a LEET ASCII art showing D.O.W (pretty much what's on the home page now lol).

Of course, once I finished most of that stuff, I then began to realize, "Sh#t, how am I going to constantly update this whenever I want to add a post?"

I then began to realize that I wasted a day or two on something that wasn't feasible. Time to restart.

# Discovering HUGO

I began to discuss what had just happened to a good buddy of mine, S0lidStat3 (visit his blog here!). He then asked me why I was trying to do it the difficult route, and admittedly I told him, "idk, I guess I like overthinking things lmao." This is where he told me about this beautiful static site generator called HUGO.

# What is HUGO?

HUGO is a "static site generator" written in one of my favorite programming languages, Go. HUGO is known for its reliability and insanely fast build times, in addition to its simplicity. For example, the text you're reading right now is written in Markdown instead of HTML, making it extremely simple to create posts.

# What is a Static Site Generator?

A static site generator is a piece of software that creates static (unchanging) HTML websites from templates and content files such as Markdown. Think about it as a way to automate the actual process of developing a page.

# Creating the Blog: Now with HUGO!

At first, HUGO was a bit of a pain in the ass as I had to figure out how everything is laid out. What to do, what not to do, and the classic breaking stuff and fixing it. By no means am I an expert on HUGO, but dang does it feel nice to use. For me personally, I REALLY enjoy the centralized aspect of the config file (which can be written in YAML, TOML, or JSON). For the config itself, it's wildly simple. Just read the docs before getting too hyper-specific with changes. If you want to see how I have mine configured, this site is hosted on GitHub Pages. Oh right! My choice of hosting!

# Why I Chose GitHub Pages to Host My Site

For those that are unfamiliar, GitHub Pages is a repo feature that allows users to host sites based off their username. The file structure is based off the branch you tell it to pull from (most of the time it's main — if it's anything else you're sick in the head). The coolest thing, though, is it's free for anyone. In addition to it being free, if you set up your custom domain, GitHub automatically gives you TLS certs, which means no headache. All you have to do is set up a CNAME record with your username and 4 A records that point to GitHub's DNS addresses. (They also offer IPv6, which is nice.)

# Conclusion

HUGO is really awesome, and if you're interested in creating a simple website, I recommend using HUGO as a framework as it's relatively easy to pick up and use. That is all for now — thank you for your time!

— Justis (D.O.W)