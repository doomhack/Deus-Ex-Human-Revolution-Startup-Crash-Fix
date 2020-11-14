# Start-up crash fix for Deus Ex Human Revolution Directors Cut.

This mod fixes a crash on startup on systems with a large number of cores.

During launch, the game calls a function which enumerates the processors (cores) in the system and sets the process affinity. (Ie. Which cores the game will run on)

On systems with large numbers of cores (Probably more than 16 or 32) this function has a bug which causes the game to crash.

This mod patches out this function call so the game will launch.

This mod is only for the Directors Cut version. It replaces build 2.0.66.0. (2.0.0 on the menu screen)
