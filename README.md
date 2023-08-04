# Slot-Machine-Project

This repository contains a simple Python implementation of a slot machine game. Players can deposit money and place bets on multiple lines to spin the slot machine reels. The game randomly generates symbols for each reel and checks for winning combinations to reward the player with winnings.

Game Rules:

The player can deposit any amount greater than zero to start the game.
The player can bet on a specific number of lines (between 1 and 3) for each spin.
The bet amount per line must be between INR 100 and INR 10,000.
If the total bet exceeds the player's balance, they have the option to deposit more money or quit the game.
The game uses a 3x3 slot machine format.
Each symbol has a different count in the machine, and each symbol also has a specific value.
The player wins if they get the same symbol on a line. The payout is calculated based on the bet and the value of the symbol.
The player can keep playing until they choose to quit or run out of funds.


The game will prompt you to deposit money. Enter the amount you want to deposit (must be a positive integer).

The game will ask you to press Enter to play or 'q' to quit.

If you choose to play, you will be asked to enter the number of lines to bet on and the bet amount per line.

The game will then display the slot machine's result, the winnings, and the winning lines (if any).

The game will update your balance based on the winnings or losses and allow you to play again.

To quit the game, press 'q' when prompted.

Note:

Please ensure that the random module is available in your Python environment as this code uses it for generating random slot machine spins. The symbols, counts, and values provided in the code can be modified to create different game variants.

Feel free to use, modify, and improve this code for your personal or educational purposes. Enjoy the game!
