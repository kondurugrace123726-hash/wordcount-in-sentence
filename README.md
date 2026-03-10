# wordcount-in-sentence
Python program to count the number of words in a sentence using simple string operations.
# Count Words in a Sentence 

## Problem Statement
Write a program to count the number of words in a given sentence.

A word is defined as a sequence of characters separated by spaces.

## Input Format
A single line containing a sentence.

## Output Format
Print the total number of words present in the sentence.

## Example

Input
Hello world welcome to python

Output
5

## Explanation
The sentence contains the following words:
Hello, world, welcome, to, python

Total words = 5

## Approach
1. Read the sentence using input().
2. Remove extra spaces using strip().
3. Use split() to separate the words.
4. Count the number of words using len().
