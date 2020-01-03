# CardsAgainstHumanity
TShock plugin to play Cards Against humanity in-game with a nice interface

This plugin adds in a Cards Against Humanity game that is not chat-based for an easy overview, players have to supply their own answers to a randomly selected question.

Each round one person gets to be the czar (judge) and picks who gave the funniest answer.

By default there are 15 rounds, and a maximum of 7 players can join.
These options are configurable in the config file.

The plugin's config comes pre-installed with around 2000 questions, so you can plug it in and start playing right away.

You need a minimum of 3 players to start a game.

The config file can be found in /TShock/CardsAgainstHumanity.json

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Commands
/cah join - Join the game
/cah leave - Leave the game
/cah answer <answer> - give your answer for the current round
/cah win <id> - choose which answer wins the round
/cah spectate - spectate the current game
/cah start - start the game
/cah stop - stop the current game
/cah lock - toggles the lock status, if the game is locked nobody else can join. (If it is unlocked players can join while the mid-game)

Permissions
cah.play - normal commands to play the game.
cah.admin - cah admin commands.

By default the game will automaticly start in a minute after 3 players join. if you wish to disable autostart you can find this in the config file.

Credit to Jewsus for making me a list of ~2000 questions

Permissions
cah.play - access to the basic commands to play the game like join, leave, answer, win, spectate
cah.admin - access to the admin commands like start, stop, lock 

[Cards Against Humanity](https://tshock.co/xf/index.php?resources/cards-against-humanity.165/)
