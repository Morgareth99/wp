wp
==

Description
===========

wp is a tiny wallpaper setter script with save/restore functionality and optional interactive mode.

Usage
=====

A usage example looks like so:

>  ~/git/wp [master]  ./wp
[wp] [wp] Usage: wp [--random|--set|--get|--save|--restore|--interactive]
>  ~/git/wp [master]  

Requirements
============

wp currently utilizes feh to set a background image (which of course easily can be changed), so you have to install feh.

Interactive Mode
================

In interactive mode, wp allows you to select a wallpaper that you like by repeatedly hitting [n] until you found a wallpaper that fits your taste. If you like one, just press [s] to save your selection and [q] to quit wp.

Random Mode
===========

--random will just select a random chosen wallpaper from your configured wallpaper directory and exit.

Restore functionality
=====================

If you like to set your last set wallpaper on log-in, you can do so by adding a line like this one to your ~/.xinitrc file:

> wp --restore

Bugs?
=====

If you think you found a bug, please report it via GitHub and I'll look into that.



