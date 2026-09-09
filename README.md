# My dwm.
This is a personal modification of [dwm](https://dwm.suckless.org/).
All credit for the original dwm project goes to the suckless.org developers and contributors. This repo contains my own modifications and configuration.
# What This is.
My aim is for this to be a fork of dwm that adds more complex floating window managment and makes it possible to run as a pure floating wm
changes are added into dwm.c and config.def.h/config.h.
# For Teacher to read.
dwm is a simple tiling wm written in c an it uses the x11 library for display data. I am planning to make it more of a floating style wm that allows 
freeform floating windows to be manipulated an moved around, i will also be modifying the manage() function to make the wm draw windows in
a spesific pattern that allignes with a floating wm better. The reason i think this will be a good project is because it solves a real issue i have ran
into as tere isnt a simple floating style window manager that has a non xml style configuration that i think can be confusing to modify unlike c writing 
this in c will also allow me to keep the wm small using like ram while im idle that is theh goal and my theory behind it is that it is because i will be 
able to handle memory managment writing in a low level language.
# This curent repo.
The current repository has not got any real changes to dwm.c so far just comments and empty functions and config.def.h has only got changes that a typical user
would make anyways like changing default binds ect.
