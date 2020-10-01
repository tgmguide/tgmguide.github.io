---
layout: post
title: Setting up Texmaster2009
---


This guide will tell you how to get Texmaster2009 running.
Normally, we'd tell you to check out the introductory guide, but unfortunately, we haven't gotten around to updating the TL;DR for it juuust yet.

Here's the steps we're taking on:
* Downloading Texmaster2009-5
* Seting up Texmaster properly
* OPTIONAL: Seting up "Termino Velocity", a custom theme

## Downloading Texmaster2009-5

First thing you need is Texmaster itself, of course. The link for that can be [Right about here.](http://mindflyer.net/tetris/texmaster/Texmaster2009-5.7z) You'll need 7-Zip to unpack the archive. If you don't have it yet, use your mighty Google powers and find any mirror to download it from. (TODO link 7-Zip website) Just unzip it anywhere and you will end up with a folder named `Texmaster2009`. Enter that folder - You should see something like this.

![Texmaster folder, fully extracted]({{ site.baseurl }}/public/img/texysetup/rootfolder.png)

From here on out, this place will be referred to as the `root` folder in the guide.

Technically, Texmaster is already ready to go, albeit with a bit of a cramped layout.
```
Assuming you have a QWERTY keyboard:
P1 Up          - S
P1 Down        - X
P1 Left        - Z
P1 Right       - C
P1 Button 1    - N
P1 Button 2    - M
P1 Button 3    - ,
P1 Button 4    - Spacebar
```

## Setting up Texmaster properly

However, of course, we can remedy this, thanks to the wonderful `Texmaster2009.ini` file we can see in the `root` folder. Open it up in a text editor of your choice - if you don't have one yet, we recommend you to give Notepad++ a try!

Now, once in here, there's a bunch of variables you can change. In the `[VIDEO]` settings, I recommend you to only change the resolution and whether you want to use fullscreen or not. The other options are a bit more advanced and don't really matter anyways. 

<p class="message">
 Take note that if you want to change the resolution, you should always work with whole numbers, multiplying the base resolution of <b>320x240</b>! Using any other resolution will make your game look very weird. For example, sinefuse, the guide maintainer, uses 1280x960 (which is 4 times the base resolution), so they've set the width to 1280 and the height to 960.
</p>

The part that's more important to us is the `[KEYBOARD]` settings, which you can find when scrolling down a bit. This only applies if you do not want to use the base key layout. Go ahead and change the `player1` variable into a `5`. This will allow us to set the correct keys by reading from the other variables labled `key_type5` right below that.

Now, unfortunately, unlike the example in the .ini file tells you to do, you can't just put the actual keys you want to use in there and have it work. What you need to do is enter specific numbers which correspond to a certain key. As for which number you have to type in for the individual keys, you will have to go into your `html` folder which you can find when you have the `root` folder open. From there, open `key.html`, and there you will have a handy list of which numbers correspond to which keys. Use the search function by pressing `CTRL+F`, type in a key, and you should be able to find the corresponding number quite quickly. Now it's just a matter of putting those numbers into the specific variables. Here is how the guide maintainer has his set up, for example:
```
key_type5_up = 119
key_type5_down = 115
key_type5_left = 97
key_type5_right = 100
key_type5_a = 106
key_type5_b = 107
key_type5_c = 108
key_type5_d = 32
```
This will result in a layout that uses A and D to go left/right, W for a sonic drop, S for a hard drop, JKL for rotations and the space bar for hold. Basically, it shifts the default layout up by one key row.

<p class="message">
 This guide is still a work in progress! Give it some time, it will be updated soon...
</p>
