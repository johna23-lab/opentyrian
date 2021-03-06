OpenTyrian
================================================================================
This version already is available for 32, 64 bits (Glibc 2.27 Ubuntu 18.04/Linux Mint 19.3) and of course the ms-dos binaries (you can play it with dosbox too)

OpenTyrian is an open-source port of the DOS game Tyrian.

Tyrian is an arcade-style vertical scrolling shooter.  The story is set
in 20,031 where you play as Trent Hawkins, a skilled fighter-pilot employed
to fight MicroSol and save the galaxy.

Tyrian features a story mode, one- and two-player arcade modes, and networked
multiplayer.

[![shot1](https://www.mobygames.com/images/shots/l/4468-tyrian-2000-dos-screenshot-level-1.gif)
[![shot1](https://www.mobygames.com/images/shots/l/484348-tyrian-2000-dos-screenshot-take-a-look-at-the-ship-s-paint.png)


== Additional Necessary Files ==================================================

Tyrian 2.1 data files which have been released as freeware:
  https://camanis.net/tyrian/tyrian21.zip

== Keyboard Controls ===========================================================

alt-enter      -- toggle full-screen

arrow keys     -- ship movement
space          -- fire weapons
enter          -- toggle rear weapon mode
ctrl/alt       -- fire left/right sidekick

== Network Multiplayer =========================================================

Currently OpenTyrian does not have an arena; as such, networked games must be
initiated manually via the command line simultaneously by both players.

syntax:
  opentyrian --net HOSTNAME --net-player-name NAME --net-player-number NUMBER

where HOSTNAME is the IP address of your opponent, NUMBER is either 1 or 2
depending on which ship you intend to pilot, and NAME is your alias

OpenTyrian uses UDP port 1333 for multiplayer, but in most cases players will
not need to open any ports because OpenTyrian makes use of UDP hole punching.

== Links =======================================================================

project: https://github.com/opentyrian/opentyrian
irc:     ircs://irc.oftc.net/#opentyrian
forums:  https://tyrian2k.proboards.com/board/5
