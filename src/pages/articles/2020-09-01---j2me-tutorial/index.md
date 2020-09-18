---
title: J2ME 
date: "2020-09-01T17:40:00.000Z"
layout: post
draft: false
path: "money-printer-go-brrr"
category: "misc"
tags:
  - "Java"
  - "J2ME"
description: "How to write J2ME apps for your Nokia 3310 Refurbished in 2020."
---

Come to think about it, quite a few personal projects I've worked on over the years came about because I felt I needed to go against the grain in terms of conditions or expectations. In this particular case, I started working on J2ME because a certain university professor said _you can do this project with any mobile technology_, which led to a conversation along the lines of:
Me: So I can go with any mobile technology I want, correct?
Him: Yes, most people do Android projects, but I've seen a few successful ones for iOS.
Me: I have a Nokia 3310 refurbished and it should be possible to write apps for that, _somehow_.

It took me a couple evenings to set things up correctly and once I got a reliable environment going, everything got much easier. (Or at least as easy as things can be when developing things for a 10-year-old platform with a heavily limited API.)

## Installation steps
These steps work for Windows and have been tested on a Windows 10 VM. I strongly recommend following them on a virtual machine, as there's going to be a certain amount of outdated software involved.

1. [Download and install Java 6.](https://www.oracle.com/java/technologies/javase-java-archive-javase6-downloads.html)
2. [Download and install Java ME Platform SDK 3.0.](https://www.oracle.com/java/technologies/javame-sdk/java-me-sdk-v30.html)

## Using Eclipse / Netbeans etc for development
Can you use Eclipse, Netbeans or any other IDE? Possibly. However, after spending a considerable amount of time trying to set it up reliably I gave up. The IDE shipped with the J2ME SDK 3.0 was good enough for me.

## Setup steps
Start the Java ME Platform SDK 3.0 app (henceforth: IDE)


All in all, there are certain technologies that are still not old enough to be considered _cool_ but turn out to be fun to work with nonetheless, and I dare say J2ME belongs to that fine club. 