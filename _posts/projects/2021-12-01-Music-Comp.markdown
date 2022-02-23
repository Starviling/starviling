---
layout: page
title:  "Music project for ARS 306"
subheadline: "Music Comp"
teaser: "A brief showcase of the program I put together for my ARS406 class."
date:   2021-12-01 00:00:00 -0500
categories: work
tags:
    - blog
    - post
permalink: "/portfolio/music-comp/"
---

I put together a small program that reads the pixel color values on the screen and plays an associated instrument. This project utilizes the Synthesis Toolkit in C++ (STK), a set of open source audio signal processing and algorithmic synthesis classes written in the C++ programming language. You can find more details [here](https://ccrma.stanford.edu/software/stk/index.html).

All of the instruments have been made to wrap operate within a certain range of frequencies so that it is still audible and isn't too ear grating to listen to.
- The blue instrument is a brass instrument that constantly increases based on the blue values on the screen.
- The green instrument is a bow instrument that continiously decreases based on the green values on the screen.
- The red instrument is a Hammond-oid organ FM synthesis instrument that constantly increases

## Demonstration of Music program I put together
<div class="flex-video widescreen vimeo">
  <iframe width="1280" height="720" src="https://www.youtube.com/embed/YeUPDA9m9rY" frameborder="0" allowfullscreen></iframe>
</div>