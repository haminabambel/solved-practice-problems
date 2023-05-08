Download Link: https://assignmentchef.com/product/solved-practice-problems
<br>
Practice 1

You need to program to simulate the rolling of two six-sided dice. The program should work by generating two random numbers, each in the range of 1 to 6, to represent the two dice. The sum of the two values should then be calculated. Use a loop to roll the dice millions of times and use a one-dimensional array to keep a count of how many times each sum appears. Here’s a snippet you can use. Assume counts is declared like this: int[] counts = new int[13];

int die1 = 1 + (int) (Math.random() * 6);

int die2 = 1 + (int) (Math.random() * 6);

int sum = die1 + die2;

counts[sum]++;

Practice 2

You need to program that will play Tic-Tac-Toe. The game board will be a 2D array. Allow two human players. Wherever the first player moves, place an X in the specified square, and place an O wherever the second player moves. Each move must be to an empty square. After each move, determine whether the game has been won and whether it’s a draw.