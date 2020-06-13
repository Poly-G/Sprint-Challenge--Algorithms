#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n) - A single while loop is O(n), this equates to O(n^3) - O(n^2), breaks down to O(n)

b) O(n log n) - The first loop running is O(n).
The second loop only runs when J is less than n. When it does. J increments.

c) O(n) - This will run as many times as needed to get down to the base-case.

## Exercise II

Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.

# Solution

1. Cut the number of floors (n) in half, and then drop an egg to see if it breaks.
2. Based on return value, you would either remove the higher or lower values of n.
3. You continue to do this until you find the right floor (f)

O(n log n)
