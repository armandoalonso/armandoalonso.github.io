---
layout: post
title: My First Blog Post
date: 2019-10-14
description: This is my first blog post, I will talk bout my new youtube channel and my game development journey.
img: football-video-series.png # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [gamedev, video]
---
This is my first blog. So yeah I started a [youtube channel](https://www.youtube.com/channel/UCxYVUzTKpE8Y1vZMyvV6Xdg) where I will be trying to create game development videos. I also started a blog where I can just talk about whatever I want, but i feel like its mostly going to be about game development stuff. In this first post I will talk about the football game i am trying to make and all the system invovled.

## Football Game Series

I had written a prototype for a football game about 2 years ago using GameMaker Studio 2. At the time i was still learning game maker, so the game was very unpolished and buggy. and I had not used Construct yet, and a new version was still in it's infancy. Over the last couple of month I think construct 3 has imporved a great amount. The addition of scriptting API has been really great. Looking back at some of my old prototypes I wanted to see if I could recreate and improve my football game. Both GM2 and C3 are structured in different ways, so it is going to take a bit of paradigm shift to rewrite the core game logic. I plan on documenting my process of creating this football in a series of youtube videos and maybe some blog posts? cause why not. I feel like having a sort of commitment will help me actaully finish something, becuase you know finsihing some thing is like the hardest part. I think the youtube videos will also help imrpove my speaking skills, becuase social interaction is not my strong suit. maybe talking to myself and recording it will help me talk to others...

## Systems

The football game I plan to create will have a few core systems. 

* Play designer (offense / defense)
* Core FSM (setup / hike / post)
* Joystick Controlled QB
* Semi Smart AI (play selection / in game actions)
* Player Stat System

![Designing Football Plays]({{site.baseurl}}/assets/img/football_playdesigner.gif)

I am not sure how much of it is scope creep, but i atleast want to create a simple but complete football experince. The goal is to be able to design the plays how you want. then call hike, and try and throw the ball to an open receiver. the thing is football is a pretty complicated sport so i have to find ways to abstract some of the complicated systems out.    
