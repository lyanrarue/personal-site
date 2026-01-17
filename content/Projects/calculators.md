---
title: Calculators
draft: false
tags:
  - for-mobile
  - react
  - frontend
---


## Back Story

A few years ago, without realizing it at the time, I ended up owing a significant amount in taxes. After digging into the issue, I discovered that my W-4 was under-withholding each pay period, even though I had filled it out correctly.

After talking with my company’s payroll department, they suggested adding an additional withholding amount each month. I didn’t want to overpay my taxes, though, I just wanted to break even and owe as close to nothing as possible the following year.

So I did some quick math: I estimated what I’d owe for the year, subtracted what had already been withheld, accounted for the amount currently being withheld per pay period, noted how many pay periods remained, and divided it out to determine the additional withholding needed. Pretty straightforward.

Of course, things change, so that number isn’t always fixed. For the past few years, I’ve been recalculating it by hand every so often. Today, I finally decided to automate the process and write some code so I could stop doing the math manually.

I should note that this is mostly vibe-coded React. I’m not a front-end developer, but I wanted something pleasant to interact with. I wrote out the formula and had Claude flesh out a very basic site with form inputs.

For future-proofing, I also asked Claude to make the setup relatively plug-and-play, so I can spin up new calculators over time by focusing primarily on the formulas as new needs arise. I will try to keep this up to date if and when I add more calculators!

Use the calculator [here](https://lyanrarue.github.io/calculators/)!