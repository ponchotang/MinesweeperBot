# MinesweeperBot
Bot written in C# to play the Windows XP version of the game.

Hello, this is my first project that I have put on GitHub. As such, I have no idea how I should be doing things, so go easy on me.

As of now, this bot can only make the very obvious moves, that is, determining if it is a mine based off of the number of unclicked tiles
being equal to the tile number being inspected. I have finished this basic algorithm, so I have decided to upload it here on GitHub as it
is 'working'.

I am now working on an algorithm that will make more complex moves and thus be capable of handling very bad starts as well as being able to 
consistently solve the higher difficulties.

For code used to manipulate the mouse as well as the windows, were done using the windows32 api and were taken from various sources from 
the internet. Everything else I have written on my own.

NOTE: This has only been tested on my own laptop, which has a resolution of 1366*768. I have no idea if the resolutions for the game
will be different on other computers/screens and whether or not the colours will be the same. As such, it is possible that it will not 
work on other computers. If this is the case, I am hoping to address this once I have fully completed the program.

Also, the Windows XP version of the game was taken from http://www.minesweeper.info/downloads/WinmineXP.html . I do not know if this
is the same version as that on actual XP systems.