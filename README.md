# Slot Machine

This is a Python program that simulates a simple slot machine game. Players can deposit money, choose the number of lines to bet on, and bet on each line. The slot machine then generates random symbols and checks for winning combinations on the selected lines.

## Usage

To use the program, simply run the `main()` function. Upon running the program, the user will be prompted to deposit money. After depositing, the user can spin the slot machine by pressing enter. The program will prompt the user to select the number of lines to bet on and the bet amount for each line.

## Configuration

The game can be configured by adjusting the following constants:

+   `MAX_LINES`: the maximum number of lines a user can bet on
+   `MAX_BET`: the maximum bet amount per line
+   `MIN_BET`: the minimum bet amount per line
+   `ROWS`: the number of rows in the slot machine
+   `COLS`: the number of columns in the slot machine
+   `symbol_count`: a dictionary containing the number of symbols of each type
+   `symbol_value`: a dictionary containing the payout value of each symbol type
