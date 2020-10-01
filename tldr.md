---
layout: page
title: Introductory guide
---

Welcome to the introductory guide! This page exists to get you up and running with playing TGM as quickly as possible, but also informing you about the differences between the multiple ways you can play it.

This guide assumes that you have at least some sort of basic knowledge of what the TGM games are. If not, It is highly recommended to check out the Wiki entries over at Tetris.wiki and have a read about it. [The page about the first game is a good start.](https://tetris.wiki/Tetris_The_Grand_Master)

We'll also assume that you're using Windows 10 as your operating system. For Linux and macOS users, the in-depth guides will be by your side however.

# Table of Contents
1. [Available methods](#section1)
2. [What is the difference between emulator and clones?](#section2)
3. [But why can't I just get the real games?](#section3)
4. [Setting up a way to play](#section4)
	* [Setting up an emulator](#section4a)
	* [Setting up a clone](#section4b)

<div id="section1"></div>
## Available methods

Now, before we continue, we need to establish *how* you'd like to play TGM, as there are several ways to enjoy it. You have a few options at hand here:
* Playing via emulation
* Using clone games which imitate TGM nearly perfectly
* Obtaining a PCB of the real games (very expensive, **not recommended for new players**)

Unfortunately, playing TGM in a truly legitimate way is extremely difficult these days, due to a constant uptrend of the prices at which the actual game PCBs are sold. That's why this guide exists - it's meant to serve as a guide to play this game without spending, quite frankly, *ridiculous* amounts of money. Because of this, this guide will *not* cover how to get a PCB working.

<div id="section2"></div>
## What is the difference between Emulator and Clones?

The difference is that in an Emulator, you play the actual games and your high scores can be submitted to [theabsolute.plus](theabsolute.plus), which is a leaderboard site for these games. Naturally, using emulators to play **pirated** copies is illegal of course, which is why **this guide will not provide direct links to any ROM images you may need.** However, if you provide your own, legally obtained ROM images to use with the emulator, it's perfectly legal. Therefore, *this guide assumes you're using your own, legally obtained ROM images.*

Clones, on the other hand, usually have *gamemodes* which play like the actual games, but due to being slightly inaccurate (we're talking very slight amounts, by the way) and due to not being the actual games, scores from clones are not permitted on the leaderboards mentioned earlier. The thing about clones however is, since they're written from the ground up, they're legal to use. 

<div id="section3"></div>
## But why can't I just get the real games?

TGM is a long-standing game series with entries being older than 20 years, so naturally, the games are no longer in production. It doesn't help that the games never found a real way into the home console market, so we are unable to enjoy these games legally unless we pay serious amounts of money for the game on japanese auction sites. Unfortunately, the producers of the games are unable to create more of these PCBs for various reasons, which doesn't help it. It should also be noted that the producer of the series doesn't like these unofficial solutions to enjoy the game, so be wary about where you talk about these other ways to play the game. **If the producer finds out about more clones, he will shut them down and/or cease production on future TGM games.** Please be careful where you share your achievements, and don't make it obvious as to whether you're emulating or not.

Lets focus on what we can do however, which is setting up either emulation or a clone to play the game on. If you want to set up an emulator, read onwards. For clones, [click here.](#clone)

<div id="section4"></div>
## Setting up a way to play

If you've made up your mind on which way you want to enjoy TGM (or maybe even both?), here are quick but still detailed guides on how to do so. If you feel more comfortable with a more detailed guide, you will find a link to the relevant one at the top of the section.

<div id="section4a"></div>
### Setting up an emulator
[For the full guide, please click here.]({{ site.baseurl }}/2020/05/03/setting-up-an-emulator/)

A TL;DR of what the full guide does:

1. Download Shmupmametgm [by clicking this link](https://github.com/MaryHal/shmupmametgm/releases/download/v2.1/shmupmametgm_windows_2.1.zip)
2. Extract the above archive to a directory of your liking, this guide (and the full guide) uses `C:\MAMETGM\` for simplicity's sake
3. Create a `roms` folder wherever you extracted the archive to
4. Shift+Right click an empty space and open a PowerShell window
5. Paste `.\mametgm64.exe -cc` to generate a `mame.ini`
6. Change the following parameters in the `mame.ini`:
  * `filter` to 0, for crispy gameplay
  * `window` to 1, unless you don't want to play windowed
  * `resolution` to a multiple of 320x240 for best results
7. Start `mametgm64.exe` normally
8. Once inside a game, adjust your inputs properly
9. Enter the service menus to enable Free Play
  * TGM: Enter `7. CONFIGURATION`, then `1. SYSTEM` and then change `1. COIN` to `FREE PLAY`. Then `5. EXIT`, `4. SAVE & EXIT` and finally `9. EXIT`.
  * TAP: Enter `Game Setting` go to `Coin Mode` and press left once to switch to Free Play. Navigate to `Exit` and then to `Exit (Reset)`.


After this, you can play to your heart's content, enjoy! Also, for clarification on any of these steps, please feel free to look at the full guide linked further up.

<div id="section4b"></div>
### Setting up a clone

<p class="message">
 This is all still a WIP. I still need to mess with these message things, shouldn't take too much tinkering though...
</p>
