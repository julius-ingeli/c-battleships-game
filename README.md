# c-battleships-game
A simple game of battleships written in C


## KNOWN ISSUES:

- ~~wrong placement of the ship will display coordidantes kinda finicky (problem occurs in horizontal placement)~~ *fixed 19/09/23 08:39; missing valid == 0; continue on the horizontal clause
- ~~selecting no to retaining ship position and then wanting to keep the boat deletes them anyways~~ *fixed 21/09/23 09:16; forgot to add return 1 on the not confirming and not retaining ship selection* 