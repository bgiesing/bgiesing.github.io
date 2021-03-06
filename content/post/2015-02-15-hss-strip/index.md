---
author: "Brandon Giesing"
title: "Home Screen Sunday: Strip UI"
description: "For HSS this week, we have a beta icon pack with unique stylings!"
draft: false
date: 2015-02-15
categories:
  - Home Screen Sunday
tags:
  - Android
  - Lollipop
  - Strip
images:
  - "/post/2015-02-15-hss-strip/cover.png"
resources:
  - src: cover.png
    name: thumbnail

---

## WELCOME TO HOME SCREEN SUNDAY!

Welcome to Home Screen Sunday, a series every **Sunday** where we look at home
screens from me or even others and explain how it works. It can be Android, iOS,
or even Desktop!

## LET'S DO IT!
For this week, we are using a pre-release icon pack that has a lot of unique stylings! Let's take a look at the Strip UI Icon Pack and my homescreen.

{{< figure src="./cover.png" alt="Strip" width="100%" >}}

### REQUIREMENTS
For this weeks theme, you will need a few things **different**.

- Strip UI Icon Pack

  > You will have to follow [these
  > instructions](https://plus.google.com/u/0/+HeatherIconic/posts/AqmAgk2H29T)
  > to download as it is in beta!

- Action Launcher

  > Setup is same as [Turbine
  > Facets](/2015/01/11/home-screen-sunday-turbine-facets) except changes listed
  > below

- Facets

  > For Wallpaper

- Xposed Framework
  - Flat Style Colored Bars
  - Battery Home Icon

  > These two modules add the battery icon in the home button and color every
  > app, even ones that don't have Lollipop colorings!

### SETUP

Time to get it started!

#### ACTION LAUNCHER

Other than what was in the Turbine Facets post, you will also need:

- `Settings > Display > Icon pack > STRIP > OK` instead of Squatch
- Set Top control in `Settings > Layout` to `Search + Menu`
- Enable Quickpage in `Settings > Layout` and put the Play Music Widget there.
- Disable `Home Screen Indicators` also under `Settings > Layout`

#### FACETS

1. Launch the App
2. Click `Months` and change to `Moods`
3. Scroll down to `Dark` and click on it
3. Click `Quest`
4. Swipe up to set.

#### XPOSED FRAMEWORK

Don't Forget to Reboot after installing!

##### FLAT STYLE COLORED BARS

Simply install from the Xposed Installer and open it up. Click `Config Buttons`
and set it to show. This will allow you to configure any app that isn't coloring
properly like Action Launcher!

Go back to your home screen and click the floating button and make both bars
fully transparent.

##### BATTERY HOME ICON

- Enable `Battery Percentage`
- Adjust Text Size and Padding if needed!

### CUSTOMIZE

Feel free to adjust as you want, if you don't want Xposed, it isn't necessary!

## ENJOY

I hope that you enjoyed this installment of Home Screen Sunday (HSS)!

If you want to send me a Home Screen to be featured, e-mail me at
<me@brandongiesing.com> starting with the subject `[HSS Blog]`!
