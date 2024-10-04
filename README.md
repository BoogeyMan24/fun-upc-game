# Fun UPC Game
### I made this because I was bored (don't judge the design too hard).


## How to Play

The rules are very simple: 
1. add all the odd positioned numbers (eg. first, third, fifth number in the series).
2. multiply the total by 3
3. add the rest of the even numbers
4. take the remainder when deviding by 10 and subtract 10 from it (unless its 0, then don't do anything)
5. The number you end up with is the final answer

# Example Game
<img width="507" alt="Screenshot 2024-10-04 at 15 27 15" src="https://github.com/user-attachments/assets/481f86b3-a26a-487f-bc89-854cb5650121">

Start off by adding all the odd positioned numbers:

8 + 3 + 8 + 7 + 5 + 0 = 31

Multiply by 3

31 * 3 = 93

Add the remainding numbers (even positioned):

93 + 9 + 8 + 1 + 8 + 0 = 93 + 26 = 119

Take the remainder of the total when divided by 10

119 % 10 = 9

Since 9 isn't 0, we have to subtract it from 10

10 - 9 = 1

The answer is 1!

## I added a timer: My personal best is 14.7 seconds!


pssst... since you actually read the README here's a hint: just keep track of the last digit (don't overflow, eg. 8 + 5 = 3)
