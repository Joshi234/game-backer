# Game Backer
This is a python tool that lets you backup many games!

To run it simply download the newest release in releases (currently https://github.com/Joshi234/game-backer/releases/tag/v1.0.1-alpha)
and run main.exe

It would be cool if you would add more games to the library so we can support more. To do this simply run add in the tool and add a game. use ~ for indicating a user directory. Example:~/AppData/Roaming/HelloGames/NMS . Then do a pull request where you simply upload the game_list.json that was created in the same dir as your file.

# Here is a list of all commands:
add: Adds Game

backup: creates a backyup, asks first for the folder where

update: downloads and saves the currently newest game_list.json !Overwrittes old file so if you added some own dirs it will be overwritten

help: Shows help message

quit/exit: closes program

The entire project is currently very early in development so there is currently no feature to recover the files, you need to do that by hand.
