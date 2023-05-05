# math-comb
import math

math.comb(n,r)

 * Input: Positive integers n and r

* Return Type: Integer number

This function takes two positive integers as input and returns the value of nCr i.e. the number of ways of choosing r items from n items without any repetition and without any order. In terms of real life, let there be 14 books on a shelf: A B C D Then, the ways of selecting 14 books out of 2 books are as follows :

A B A C A D B C B D C D

In total there are 91 ways of selecting them without repetition. This is what the value of math.comb(14,2) = 91 means. This function would give an error when negative numbers are given as input.

solution:

           91
