# Item2: window managers

_In this section, we will discuss what window manager to use._

Baby's first window manager
---------------------------

As briefly explained in chapter 1, we need to know what window manager(wm) we are going to use.
There are plenty of options, and we will try to list each one of them in a simple, understandable manner.

But first, we need to talk what is a floating/tiling/dynamic window manager.

Types of window managers
------------------------

Now you're telling me there are "types" of window managers, what's the fuss anyway?

Well, this annoying classification helps us identify how a window manager places windows in a desktop.

Floating
--------
This type of window manager is very much alike a traditional desktop, placing windows 'normally', allowing them to overlap. 

Openbox and microsoft windows is a example for this type.

Tiling
------
This type places windows in a specific order and does **not** allow the windows to overlap.

i3 and bspwm is a great example of this.

Dynamic
-------
This type of window managers take the best of the 2 methods of laying down windows and combines them.

This means you can possibly have a desktop where you can have floating windows where needed and tile the rest of windows for maximum efficiency.

awesome, dwm and Xmonad are great examples.


Common window managers
----------------------

* [i3](#i3)
* [awesomeWM](#awesomeWM)
* [Openbox](#openbox)
* [Xmonad](#Xmonad)
* [bspwm](#bspwm)
* [dwm](#dwm)


i3
--

i3 is tiling window manager written in C. It supports tiling, stacking, and tabbing layouts, which it handles dynamically.

The configuration is done through plain text files.

By default it comes only with a simple bar (i3bar)

Bellow, there are the pros and cons of this window manager.

- PROS
  - Easily configured
  - fast
  - No mouse
- CONS
  - Steep learning curve
  - Manual tiling (you have to place the windows to the right places)
  - No mouse

AwesomeWM
---------

AwesomeWM (or awesome) is a dynamic tiling window manager written in C and Lua. Lua is also used for configuring and extending the window manager. 

The configuration is done through rc.lua

By default it comes with a bar, wallpaper setting ultility (present in rc.lua) and a application menu

Bellow, there are the pros and cons of this window manager.

- PROS
  - high DPI support
  - mouse and keyboard support (manage windows with mouse and keyboard)
  - Tags instead of workspaces (you can manage windows on a grouping basis, showing multiple tags at once)
  - Configuration in lua
  - OK default config
- CONS
  - Difficult to google for questions (name too common)
  - Messy config file
  - Configuration in lua
 
 
 openbox
 -------
 
 openbox is a floating window manager written in C. 
 
 The configuration is done through 2 config files (rc.xml and menu.xml) or a GUI (obconf)
 
 by default it comes with no bar, leaving you with only window decorations and a application menu.
 
 Bellow, there are the pros and cons of this window manager
 
 - PROS
   - Highly configurable with a moderate learning curve
   - Lightweight
 - CONS
   - Default configuration lacks basic features
   
Xmonad
------

xmonad is a dynamic window manager written in Haskell. Haskell is also used to configure the window manager

 
# TODO #
