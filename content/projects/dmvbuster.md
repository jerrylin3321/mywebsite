---
title: "DMV Buster"
date: 2020-01-01
cover: "/projects/dmv.jpg"
link: "https://github.com/jerrylin3321/dmvbuster"
draft: false
---
I'm a college student trying to grab an appointment for a behind-the-wheel test. Unfortunately, appointments are literally booked out three months in advance. There are occasional openings when someone cancels, but these are hard to find and usually snatched up instantly. I went looking for bots online to automate this appointment search for me, but none of them work ever since the DMV deployed a ReCaptcha on the appointment finder page.

To solve this, I integrated the automated captcha-solving extension Buster with the existing GitHub repo Stalk-the-DMV, and added an automatic appointment scheduling feature. This bot will search through a list of DMV offices, logging down available appointments, and if an appointment is within a specified number of days, it'll automatically schedule it for you.