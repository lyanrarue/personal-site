---
title: Board
draft: false
tags:
  - for-mobile
  - react
  - frontend
---

![Board UI Screenshot](_assets/board.png)

See Board Live [Here](https://lyanrarue.github.io/board/)!

## Back Story

In early 2025, I had started to plateau in my climbing ability. I took a deep diving into training for climbing and started [hangboard training](https://www.rei.com/learn/expert-advice/how-to-use-a-hangboard-to-train-for-rock-climbing.html).

I was pretty dissatisfied with the off the shelf apps I could find to track my hangboard workouts. The UIs were either clunky, lacked the customization I needed entirely, or locked them behind premium paid plans. As a result, I started to just use my phone's timer.
Tracking timing and reps and sets while also hanging my entire body weight of a tiny edge got old fast though, so one night I resolved to make Board.

I sat down and laid out the following requirements:

1. An accurate Timer feature
2. Automatic Set/Rep Count Tracking
3. The ability to manually skip and reverse both reps and sets
4. Automatic roll-over between reps and sets with play/pause functionality when the timer ran down
5. Mobile Friendliness
6. Simple User Experience

The actual development was pretty seamless with a simple implementaiton. I's a static React site with some static data I put in specicically for my protocol (One day I'd love to make the protocol customizeable with localStorage), but it works perfectly for my training!
