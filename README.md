# Artificial-Intelligence - Cryptarithmetic-Problem

# Project Description: 
Design and implement a program to solve Cryptarithmetic problems as shown in the figure below: 
![image](https://github.com/AnuOscar2308/Artificial-Intelligence---Cryptarithmetic-Problem/assets/83712797/da7495c6-ab89-49e4-97cc-fef286126e48)

where 𝑥1 to 𝑥13 can be any capital letter from A to Z; some letters may occur more than once. Each letter stands for a distinct digit; the aim is to find a substitution of digits for letters such that the
resulting sum is arithmetically correct, with the added restriction that no leading zeros are allowed. The domain for 𝑥9 is therefore {1}, the domain for 𝑥1 and 𝑥5 is {1,2, … , 9} and the domain for variables 𝑥2 to 𝑥4, 𝑥6 to 𝑥8, and 𝑥10 to 𝑥13 is {0,1,2, … , 9}. You can introduce auxiliary variables and specify their domains to represent carry overs from previous columns. After this, you can set up a set of constraints for the problem.

# Implementation: 
Implement the Backtracking Algorithm for CSPs in Figure 1 below to solve this problem. Implement the function SELECT-UNASSIGNED-VARIABLE in the algorithm by using the minimum remaining values and degree heuristics. Instead of implementing the least constraining value heuristic in the ORDER-DOMAIN-VALUES function, simply order the domain values in increasing order (from lowest to highest.) You can skip the implementation of the
INFERENCE function. 

# Input and output files: 
Your program will read in values from an input text file and produce an output text file that contains the solution. The input file contains three rows (or lines) of capital letters:
LLLL
LLLL
LLLLL
The first and second rows contain four capital letters and the third row contains five capital letterswith no blank space between letters. The output file should follow the following format
DDDD
DDDD
DDDDD
where the Ds represent digits from 0 to 9 with no bank space between the digits.
