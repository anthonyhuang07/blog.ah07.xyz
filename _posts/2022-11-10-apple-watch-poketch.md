---
title: How to Install the Pokétch App on Apple Watch
author: anthonyhuang07
date: 2022-12-14 12:42:00 -0400
categories: [Software, Apple Watch]
tags: [software, tech, technology, apple, apple watch, xcode, pokemon, poketch]
---

## What is the Pokétch App?

The Pokétch App is an app recreating the Pokétch in Pokémon Diamond and Pearl. It has most features that the original Pokétch includes, such as a Dowsing Machine. (Of course, it wouldn't work lol)

You can find the app here: [https://github.com/IdreesInc/Apple-Watch-Poketch](https://github.com/IdreesInc/Apple-Watch-Poketch)<br>
Learn more about the app here: [https://idreesinc.com/about-poketch.html](https://idreesinc.com/about-poketch.html)

![poketch clock](https://github.com/IdreesInc/Apple-Watch-Poketch/raw/main/Resources/device-screenshots/simulator-screenshot-digital-watch.png)

### Requirements

**Any Mac Computer** - You need to use Xcode to sideload the app onto the Apple Watch. This is the only method available.

**Xcode** - Just a simple app on the App Store, though it is 7 gigabytes, so I would clean up some space!

### Downloading the files

To start, head to the Releases tab in GitHub page. Click on Build 1.1, or the latest version there is. Once you're in, download the **Source Code (zip)**. Do not download the Poketch.ipa, as that won't work in our situation. Once you downloaded it, open it to extract it.

<img src="../../assets/img/images/2022-11-10/1.png" alt="github" style="border-radius: 0.8rem"/>

Next, open the file ***Poketch.xcodeproj*** inside the folder. It should open a new window in Xcode.

### Setting up

I may go a bit out of order here, but it doesn't matter, it will still work.

First, head to the menu bar and click *Xcode > Settings*, then head to the Accounts tab. There, press the **+** button to add your Apple ID. This will be needed for the sideloading process.

<img src="../../assets/img/images/2022-11-10/2.png" alt="xcode accounts" style="border-radius: 0.8rem"/>

Next, on the sidebar, click on Poketch, then in each of the targets, click on one of them, and click Signing & Capabilities, then Teams, then your Apple ID you entered. You must do this for every target, or else the code will not build.

<img src="../../assets/img/images/2022-11-10/3.png" alt="xcode signing" style="border-radius: 0.8rem"/>

## TO BE CONTINUED