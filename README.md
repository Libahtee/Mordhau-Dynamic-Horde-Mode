# Mordhau-Dynamic-Horde-Mode

This is  a Mordhau gamemode mod I made using the unofficial Mordhau sdk (In Unreal Engine blueprint).

The original gamemode is a fight against waves of AI controlled enemies, predetermined by the map maker. The mod I wrote allows anyone running a server to dynamically change the amount of enemies spawning and features an endless mode, which instead of the game ending at the end of the last wave, it'll restart from the beginning with the option to increase amount of enemies each cycle and will only end when the players lose.

When I originally made this, it spawned all the enemies at the beginning of the wave, however I quickly found that if anymore than 150 enemies are alive at one time, the game begins to slow down to an unplayable crawl, so I also introduced a limit which can be changed in the config.
