# linux-bingo
Created a bash program to play a game called LINUX (aka BINGO)

HOW TO PLAY:
User runs LINUX with a Card (basically, a 5x5 matrix of integers). LINUX "calls" (provides) random numbers one-by-one. Each time a number is called, if that number appears on the user's Card, it is "marked". User wins when a row, or column, or all 4 corners, becomes marked.

LINUX PROGRAM INPUT:
User supplies input in A FILE, whose name is sent as an argument to the program ($1). Input file contains: a seed number (an integer, starting in column 1, with no extraneous whitespace around it), followed by 25 numbers comprising the LINUX Card (arranged as a matrix, as above). The input file must have exactly 6 lines. e.g., you might run your game as follows:
> LINUX input1
where file input1 contains the 6 lines:
1063
12 23 42 55 74
04 19 34 46 72
07 17 00 51 69
11 30 44 56 62
09 27 40 47 67
