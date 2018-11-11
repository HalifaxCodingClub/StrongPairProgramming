# StrongPairProgramming
Session of 13/11/18



## 1. Reverse Captcha

The captcha requires you to review a sequence of digits (your puzzle input) and find the sum of all digits that match the next digit in the list. The list is circular, so the digit after the last digit is the first digit in the list.

For example:

    1122 produces a sum of 3 (1 + 2) because the first digit (1) matches the second digit and the third digit (2) matches the fourth digit.
    1111 produces 4 because each digit (all 1) matches the next.
    1234 produces 0 because no digit matches the next.
    91212129 produces 9 because the only digit that matches the next one is the last digit, 9.

[Problem](https://github.com/HalifaxCodingClub/StrongPairProgramming/blob/master/ReverseCaptchaProblem)
 / 
[Solution](https://github.com/HalifaxCodingClub/StrongPairProgramming/blob/master/ReverseCaptchaProblemSolution)


## 2. Advanced Reverse Captcha


Now, instead of considering the next digit, it wants you to consider the digit halfway around the circular list. That is, if your list contains 10 items, only include a digit in your sum if the digit 10/2 = 5 steps forward matches it. Fortunately, your list has an even number of elements.

For example:

    1212 produces 6: the list contains 4 items, and all four digits match the digit 2 items ahead.
    1221 produces 0, because every comparison is between a 1 and a 2.
    123425 produces 4, because both 2s match each other, but no other digit has a match.
    123123 produces 12.
    12131415 produces 4.

[Problem](https://github.com/HalifaxCodingClub/StrongPairProgramming/blob/master/AdvancedReverseCaptchaProblem)
 / 
[Solution](https://github.com/HalifaxCodingClub/StrongPairProgramming/blob/master/AdvancedReverseCaptchaProblemSolution)


## 3. Checksum Calculator

For each row, determine the difference between the largest value and the smallest value; the checksum is the sum of all of these differences.

For example, given the following input:

5 1 9 5

7 5 3

2 4 6 8

    The first row's largest and smallest values are 9 and 1, and their difference is 8.
    The second row's largest and smallest values are 7 and 3, and their difference is 4.
    The third row's difference is 6.

In this example, the example's checksum would be 8 + 4 + 6 = 18.

[Problem](https://github.com/HalifaxCodingClub/StrongPairProgramming/blob/master/ChecksumCalculatorProblem)
 / 
[Solution](https://github.com/HalifaxCodingClub/StrongPairProgramming/blob/master/ChecksumCalculatorProblemSolution)


## 4. Advanced Checksum Calculator

This time the goal is to find the only two numbers in each row where one evenly divides the other - that is, where the result of the division operation is a whole number. Find those numbers on each line, divide them, and add up each line's result.

For example, given the following input:

5 9 2 8

9 4 7 3

3 8 6 5

    In the first row, the only two numbers that evenly divide are 8 and 2; the result of this division is 4.
    In the second row, the two numbers are 9 and 3; the result is 3.
    In the third row, the result is 2.

In this example, the sum of the results would be 4 + 3 + 2 = 9.

[Problem](https://github.com/HalifaxCodingClub/StrongPairProgramming/blob/master/AdvancedChecksumCalculatorProblem)
 / 
[Solution](https://github.com/HalifaxCodingClub/StrongPairProgramming/blob/master/AdvancedChecksumCalculatorProblemSolution)
