profile-swapper
===============

Shell utilities for swapping application config profiles under linux. Built mostly for swapping out game profiles on a media pc. Currently includes a framework for swapping config directories (still WIP), and specific scripts for swapping profiles for FTL and Rogue Legacy.

Motivation
----------

My roommates and I keep a pc in the living room mostly for playing steam games. Because the machine is shared, we run into problems with games that lack profile support, as we can't keep progress separate between different players. This is particularly severe with games like FTL or Undertale, that support only a single in-progress save at a time--it's hard to start a new game without wiping out someone else's progress. Even for games with unlimited save slots, it would be nice to be able to keep different configurations between different players. `profile-swapper` aims to solve this by swapping out the relevant save files and configuration files.
