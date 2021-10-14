# DailyCodingProblems

A collection of coding problems I have completed in code sandbox

## Problem 001

Given an array of integers, return a new array such that each element at index i of the new array is the product of all the numbers in the original array except the one at i.

For example, if our input was [1, 2, 3, 4, 5], the expected output would be [120, 60, 40, 30, 24]. If our input was [3, 2, 1], the expected output would be [2, 3, 6].

Follow-up: what if you can't use division?

[Solution](https://codesandbox.io/s/daily-coding-001-0nw67)

## Problem 002

Given a list of numbers and a number k, return whether any two numbers from the list add up to k.

For example, given [10, 15, 3, 7] and k of 17, return true since 10 + 7 is 17.

Bonus: Can you do this in one pass?

[Solution](https://codesandbox.io/s/daily-coding-002-tk8y3)

## Problem 003

### Tower of Hanoi

There are three towers. The objective of the game is to move all the disks over to tower #3, but you can't place a larger disk onto a smaller disk. To play the game or learn more about the Tower of Hanoi, check the Resources tab.

Create a function that takes a number discs as an argument and returns the minimum amount of steps needed to complete the game.

### Examples

towerHanoi(3) ➞ 7

towerHanoi(5) ➞ 31

towerHanoi(0) ➞ 0

### Notes

The amount of discs is always a positive integer.

1 disc can be changed per move.

[Solution](https://codesandbox.io/s/daily-coding-003-tucn6)

## Problem 004

Create a function which returns the number of true values there are in an array.

### Examples

countTrue([true, false, false, true, false]) ➞ 2

countTrue([false, false, false, false]) ➞ 0

countTrue([]) ➞ 0

[Solution](https://codesandbox.io/s/daily-coding-004-xfe6m)

