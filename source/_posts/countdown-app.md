---
title: countdown-app
summary: React & Electron app
casestudy: true
thumb: images/countdown-app-thumb-alt.jpg
image_post: /images/countdown-app-post.jpg
repo: https://github.com/tjallen/countdown-app
date: 2016-11-10 12:06:04
page_links:
- link_text: Web build
  link_url: /projects/countdown-app
- link_text: Electron releases
  link_url: https://github.com/tjallen/countdown-app/releases
tags:
- JavaScript
- React
- Electron
- Webpack
---

A countdown timer app with web and desktop builds, built with [React](https://facebook.github.io/react/) and [Electron](http://electron.atom.io/). Also holds the current world record for most generic name.

This began as an hourly chime component but got overtaken by a feature creep binge, becoming a countdown timer with some extra features, such as:
- Player controls: pause & resume, clear, reset, add one minute
- Toggling timer loop/repeat
- Setting timer labels
- Volume controls for the audio alert using my [react-simple-range](https://github.com/tjallen/react-simple-range) module

Timer ticks/updates are fired by a looping setTimeout which attempts to self-correct for drift due to JavaScript's single threaded nature, allowing greater accuracy than would be achievable by setInterval.