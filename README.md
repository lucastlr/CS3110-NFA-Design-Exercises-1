# CS3110 NFA Design Exercises 1
Lucas Taylor
CS 3110.01-1
## Problems:
1. (#6) {string s| s starts with 10 } 
2. (#13) {string s| s contains at least 2 1's }
3. (#16) {string s| every odd position of s is 1, starting at 1 in positional index }
4. (#22) {string s| s has 3k+1 of 1's, where k>=0 or odd number of 1's} 
5. (#23) {string s| s has odd length or s=01}
## Summary of Learning:
1. Problems 22 and 23 gave me the most trouble because of the or statement, meaning I had to keep track of multiple states at once. I was also uncertain about drawing the tree of computation for 23 since the branch that checks s=01 ends before the rest of the string is processed by the other branch. I picked the problems at random so there were not any I intentionally avoided, and I primarily referenced the examples completed in class to guide me for this assignement.
2. I did not encounter any gold strings during the assignment and I made sure to check edge cases in my test strings. An exmaple of one string I did find interesting was "0100" for problem 23, since although it starts with 01 it does not equal 01 and it is not of odd length so it is rejected.