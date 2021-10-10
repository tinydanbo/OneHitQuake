# OneHitQuake

OneHitQuake (OHQ) is an extremely small, simple mod for Quake (1996), based on the 1.06 version of the QuakeC source code.

OHQ reduces the player's maximum health to 1, maximum armor to 0, and reduces the pentagram's protection time to 1 second. On the bright side, fall damage is no longer applied.

All health pickups and armor pickups are consumed without granting any benefit, so that any triggers that rely on picking up such items can still work.

You can still drown.

I don't know if it is possible to clear the game with this mod. I know [Episode 1 can be done on Nightmare](https://www.youtube.com/watch?v=_Atl0SZOwb8), and I know that *one* forced drowning spot in The Wizard's Manse can be biosuit'd by a particularly nimble player.

## Usage

Just like any other Quake mod. Get a release zip, extract the ohq directory inside your Quake directory, then either:

* Run your quake executable from the command line appended with " -game ohq", or create a shortcut to do so.
* Type "game ohq" into the terminal on starting Quake.

This is only intended for usage with id1, it won't work with maps/mods that have their own progs.dat file.

Works on vkquake and quakespasm-spiked. Should work on any engine, though.

I compiled it using [FTEQCC](https://fte.triptohell.info/downloads), I don't know much about other compilers.