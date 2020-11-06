---
title: Convincing slime pathfinding with good enough fluid simulation
layout: post
author: Seth
image: haxe_logo.svg
excerpt_separator: <!-- excerpt-end -->
---

<div style="background-color: #FFBF60;">
    <img src="/assets/images/heaps_logo.svg" alt="heaps logo" style="width: 100%; height: auto; margin: auto; display: block; ">
</div>

<!-- excerpt-start -->

The design vision for SlimeBreaker requires us to display thousands of slimes on screen at once. There are a many technical challenges to overcome in order to do this, but the hardest one is handling pathfinding for that many agents.

<!-- excerpt-end -->
<img src="/assets/images/haxe_logo.svg" alt="haxe logo" style="width: 100px; height: auto; float: left; margin-right: 12px;">

I decided to make the switch from Unity to Heaps because I prefer to work primarily in code, and I
got tired of constantly fighting with the Unity editor. With compilation times have getting progressively worse the last few versions of Unity, I finally pulled the trigger and switched. I've been watching Heaps
for a few years and the list of successful commercial games using it is impressive.

My brother Zane is the other programmer at Glass Arrow Games, and so far he's enjoyed working with Heaps just as much as I have. We're going to keep this blog updated to document what we learn along the way, both to help out other programmers looking for answers and so that we have an easy repository when we inevitably forget how we solved a problem.
