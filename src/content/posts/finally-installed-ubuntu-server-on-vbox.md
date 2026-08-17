---
title: Finally installed Ubuntu Server on vbox
pubDatetime: 2026-08-18T00:41:00.000+06:00
author: Shafat
description: I write about the experience of installing Ubuntu Server on vbox
  and first few commands
featured: false
draft: false
tags:
  - general
---
Today after almost a week of procrastination, I have been able to install Ubuntu Server 26.04 on my Virtualbox. I also logged in using open ssh server to the server from my OpenSUSE machine. This is not the first time I did it though. I remember may be later last year I determined to complete Linux Upskill challenge. I installed Ubuntu Server first time on my Virtualbox following the challenge module. But then I couldn't complete the challenge and I think after 2nd or 3rd day I dropped out. This time it is not a challenge but a course. And I think this time I felt the friction point very early. I don't think I had to chat to ai to fix virtulbox error that didn't let me run the installer of Ububtu server on OpenSUSE. However this time I faced this issue. Today I also faced a problem while trying to login using ssh. I faced a problem that denied me to login after successful connection to my server. The problem was my user id wasn't registered. Then I revisited the walkthrough and saw a problem in my command. What id did was that I used this command to login:

`ssh 192.168.110.80`

Which successfully established the connection and asked for password. I gave the password and failed to login.

Then after careful observation I learned the actual way is:

`ssh user@192.168.110.80`

That's the learning I thought I should write in today's blog post. 

There's a big video module of roughly 1 hour in the foundation module. 

I have completed around 20-30 minutes.

I have to complete it within tomorrow that's my goal.

Today I also got an invitation from Mischa about his next live event on 25 Aug. 

He will talk about career path.

In the email he shared something I never heard of --
> 93% of hiring managers say they can't find enough people with open source skills

That's huge. 

I think if I can build up a skill in this sector it would be huge. 

That's it for today. 

Will write next post after completing the 1 hour module.
