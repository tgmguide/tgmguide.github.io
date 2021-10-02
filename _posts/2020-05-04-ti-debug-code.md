---
layout: post
title: How to enable Ti's debug code
---

This guide is kept as concise as possible and is split into two parts. The first part is a "preparation" part, you only have to do these steps **once.** The steps in the second part are what you actually have to do every time in order to enter debug mode in Ti.

## Preparation (only required once)

1. Set the game to free play, or else it doesn't work.
  * This is probably in order to prevent trolls from just putting it in at public Ti cabinets.
2. Create an account with the initials `MII` and with the password `A B A B D C`.
3. Start a game in any game mode and top out.
  * The idea is that we want to get to the title screen as fast as possible from here.
4. Say "NO" to continue when the countdown shows up, then press start once while it says "GAME OVER" to quickly skip the game over text.
5. The game will ask you to press start again for a new game (doing this would, well, start a new game and show the account menu). We don't want that, press D instead to go to the leaderboards menu.
6. Press Start once to exit the leaderboards and return to the title screen.

And that's the initial prep done. Remember: **You do not have to repeat these steps once you've done these.**

## Entering debug mode (always required after restart)

Make sure you are on the title screen where the logo is. Not inside the demo/attract mode or the leaderboards!

1. Hold A and B, then press start while the logo is still on the screen.
2. We want to use the account `MII` that we made in the prep. Enter those initials.
3. For the password, you want to press ABAB normally as if you enter the password.
4. For the last two buttons, you first press and then hold D. Keep holding D and don't let go until this guide says so!
5. For the final button, press and hold C while still holding D. Do not let go until you can see the summary of the account **inside the playfield**, such as how many times you played or what grades you've got. Basically what appears after the flashing OK disappears.

And now, debug mode is active until you **shut down the game**. Score saving is disabled!

## What you can do in debug mode
  * While selecting Master mode, hold Up to force a promotion exam for the next highest grade.
  * While selecting Master mode, hold Down to force a demotion exam instead.
  * In game, pressing C will instantly set your level to x99, with x being your current section, so for example if you are at level 214 and press C, you will be at 299 instead.
    * However, during Master mode, if you do it at level 900+, you will be at 998 instead.
  * Holding start while locking a piece will **unconditionally** cause a 4-line-clear at the bottom of the stack. Where you place the piece and what piece it is does not matter, as long as it can lock normally (read: It's impossible to Tetris from a piece that causes a game over)

If there are any things I have missed, please submit a pull request to the repository and I will add the info.
