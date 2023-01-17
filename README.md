# CS-1714-final-project
Final project for CS-1714 Programming 2, written in C.

## assignment
[assignment pdf](project-3-assignment.pdf)
The assignment is to implement a player-vs-computer game outlined in the above pdf. The program takes no input other than the number of champions each player starts with to generate their bench of champions. The rounds are then played out automatically based on the rules outlined in the assignment, eventually determining a winner.

## sample output

```                                               
> ./project3Exe 5
============= PLAYER 1 V PLAYER 2 SHOWDOWN ============

----- ROUND 1 -----
Player 1: T7 F4 F4 S3 F2 
Player 2: M7 T7 S6 S6 M5 
Player 1 is a TANK and Player 2 is a MAGE
Player 1 (TANK) loses and loses 1 champion(s).
Player 2 (MAGE) wins and gains 1 new champion(s).

----- ROUND 2 -----
Player 1: F4 S3 F2 
Player 2: T7 S6 S6 M5 T1 
Player 1 is a FIGHTER and Player 2 is a TANK
Player 1 (FIGHTER) wins and gains 1 new champion(s).
Player 2 (TANK) loses with no gains or losses.

----- ROUND 3 -----
Player 1: T6 S3 F2 
Player 2: S6 S6 M5 T1 
Player 1 is a TANK and Player 2 is a SUPPORT
Player 1 (TANK) wins and gains 1 new champion(s).
Player 2 (SUPPORT) loses with no gains or losses.

----- ROUND 4 -----
Player 1: S5 S3 F2 
Player 2: S6 M5 T1 
Player 1 is a SUPPORT and Player 2 is a SUPPORT
Player 1 (SUPPORT) ties and loses 1 champion(s).
Player 2 (SUPPORT) ties and loses 1 champion(s).

----- ROUND 5 -----
Player 1: F2 
Player 2: T1 
Player 1 is a FIGHTER and Player 2 is a TANK
Player 1 (FIGHTER) wins and gains 1 new champion(s).
Player 2 (TANK) loses with no gains or losses.

============ GAME OVER =============

Player 1 ending champion list: S6 
Player 2 ending champion list: 

Player 2 ran out of champions. Player 1 wins.
```
