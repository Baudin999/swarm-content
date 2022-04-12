---
author: Carlos Kelkboom
description: 
    Writing a blog engine is something I've always wanted to 
    do. In this blog-post I will go over the ideas I've 
    managed to put into this new engine called 'swarm'.
tags: 
    - Craftsmanship
date: 12-04-2022
---

# How to write a blog engine


I've always wondered why content was always entered into a blog engine like Wordpress or medium.com. I've 
always enjoyed writing with tools like LaTeX or Markdown. Anothing thing which always amazed me was how
easilly someone distanced themselves from their content. 

These little amazements have led to me wanting to write a content engine for a very long time and finally
I've had some time to write one. The tool is called `swarm` and is an open-source tool which is created
with the following attributes in mind:

 * 100% cookieless (unless you choose to log in...)
 * A static as possible. Except for a few interations (like posting comments) eveything should be generated
   as simple and static HTML.
 * Hosted with near $0 costs.
 * Lean against edge-computing
 * Have a dark theme to [save energy](https://www.howtogeek.com/407860/heres-when-a-dark-theme-can-save-battery-power/).
