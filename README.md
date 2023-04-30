Download Link: https://assignmentchef.com/product/solved-guessing-game
<br>
5/5 - (1 vote)

Write a well-documented Python program that:• Generates a random number between 1 and 100.• Allows the user 10 tries to guess what the number is.• Validates the user input (if user-input 100 or user-input&lt;0) then this is invalid input and should not cost the user to lose any tries.• Gives feedback for each time the user makes a guess. The feedback tells the user whether the number entered is bigger, smaller, or equal to the number generated (and exits the program).• Tells the user if they lost after he/she consumes all the 10 tries. Gives the user 10 tries to guess the number. If the user exhausts the 10 ties. The user loses.Now, this is a very typical program. But we will add a twist to it. After 2 unsuccessful tries, the program should start offering hints for the users (by having the user input the number 0).·      Each hint should be generated within a function of its own.



·      Each hint will cost the user two tries (the program should indicate this to the user)

·      The user is allowed a max of 3 hints only.

·      The program should randomly pick which hint it is going to use and display to the user.

The hints are of your choice, but here are a couple (feel free to introduce others):

1-         The number is bigger than or equal the square of some X (X is an integer and is the largest integer square that is less than the user input)

2-     The number is smaller than or equal the square of some K (K is an integer and is the smallest integer square that is larger than the user input)

3-      The number is a multiple of some Y (Y is an integer)

4-      The number is even or odd

5-      The number is one digit