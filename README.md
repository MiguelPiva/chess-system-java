# Playing the game
``` python 
8 R N B Q K B N R
7 P P P P P P P P   # Black pieces (yellow)
6 - - - - - - - -
5 - - - - - - - -
4 - - - - - - - -
3 - - - - - - - -
2 P P P P P P P P   # White pieces
1 R N B K Q B N R
  a b c d e f g h

Captured Pieces:
-> White: []        # White pieces that have been captured
-> Black: []        # Black pieces that have been captured

Turn: 1
Waiting player: WHITE
```
+ When the match starts, the interface will look like the one above. Some colors will be different, and these comments with "#" will not be there;
+ Allowed positions are from **a1** to **h8** (lowercase letter + number);
+ When any player performs a **check** or a **checkmate**, a message warning the opponent player will be displayed below "Waiting player: ";
+ This game was made as a java practice for Nelio Alves's course.
