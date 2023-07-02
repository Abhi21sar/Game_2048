# Game_2048
The classical game of creating the digit 2048 by freefall of numbers.

2048 is an exciting game. It’s a sliding tile puzzle game that involves numbers. The target is to create the number 2048.

In this project, I created an interactive version of the game 2048. I didn't create any graphical interface for now. The console will be used as an input interface to take the input move from the player and to display the current configuration of the board.

Some Details about the game-

When we start the game, two cells are populated with a number from the set {2, 4}.
A player can move left, right, up or down in one move.
Whenever a player plays a move, all the cells move in that direction and adjacent cells of the same value merge into one cell of double the value.
After merging, a random cell out of the empty cells gets a value of either 2 or 4. Note that the value 2 appears much more times than 4
The game gets over when either a 2048 cell has been formed, in which case the player would win Or all the cells are filled and no valid moves are left to perform, in which case the player loses.
Random Number Generation-

Linear Congruential Generator is a most common and oldest algorithm for generating pseudo-randomized numbers. The generator is defined by the recurrence relation:

Xn+1 = (aXn + c) mod m where X is the sequence of pseudo-random values m, 0 < m - modulus a, 0 < a < m - multiplier c, 0 ≤ c < m - increment x0, 0 ≤ x0 < m - the seed or start value

We generate the next random integer using the previous random integer, the integer constants, and the integer modulus. To get started, the algorithm requires an initial Seed, which must be provided by some means. The appearance of randomness is provided by performing modulo arithmetic..

Additional Info
Inspired by the swift version of the game which can be found here https://github.com/austinzheng/swift-2048

The original game can be found at http://gabrielecirulli.github.io/2048/, as can all relevant attributions. 2048 is inspired by an iOS game called "Threes", by Asher Vollmer.

About
The classical game of creating the digit 2048 by freefall of numbers.

Resources
 Readme
 Activity
Stars
 1 star
Watchers
 1 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
C++
100.0%
Footer
© 2023 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
