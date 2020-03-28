# cdda-fewer-farms-mod
A simple Cataclysm: Dark Days Ahead mod. Reduces the maximum number of the various types of farm that can spawn in each overmap.

A while back I pondered the fact that, put simply, the maximum number of occurrences plus the sheer number of different variants for farms means that an overmap can end up containing a downright ridiculous number of farms.

Of course, one solution to those who find them to be too abundant would be a regional blacklist mod to cull them, or a series of overmap special edits to backlist most variants. However, I decided to go for an application of the latter method with a less drastic implementation.

So instead, I soon hit upon the idea of making most variants not just only spawn a maximum of 1, but to make them count as unique. This does not actually make them unique per world (though many specials in CDDA and in mods would benefit from being ABLE), but rather it is effectively equivalent to [ 0, 1 ] or [ 1, 1 ] occurrences, with the added option of specifying a desired percent chance to determine how often they should spawn.

By doing so, instead of sticking with [ 0, 1 ] and leaving it up to the game to determine if it feels like it's had its fill of farms, I can more consistently encourage it to spawn each variant of farm about a third of the time per overmap.
