# Objectives

An understanding of the following concepts and techniques:

- algorithmic complexity
- runtime performance
  - how to measure
  - how it relates to algorithmic complexity
- abstract data types (ADT)
- array-based versus linked lists
- getting started with iterators
- automated unit testing using JUnit
  - testing for exceptions
  - test fixtures and assertions
  
# Instructions

The key idea is to think about this lab like a physics experiment! 
You will set it up and then take measurements.

1. Review the code.
2. Fix the syntax errors (if any, though there probably aren't any).
3. Run the code for various inputs to gain an understanding of what it does.
4. Complete the items marked TODO in the code and get the tests to pass.
5. Conduct the performance measurements: you will find the running times in the test report.
6. Create a new doc folder in the project.
7. Create a document called README.txt in doc and answer the various TODO Questions embedded in the code.
8. Add README.txt to the Git project, then Commit and push your code to Bitbucket.


# Test Performance Questions
These are the different run times when changing the SIZE variable 
1. SIZE = 10 -> 7-10ms
2. SIZE = 100 -> 8-10ms
3. SIZE = 1000 -> 15-20ms
4. SIZE = 10000 -> 22-27ms
5. SIZE = 100000 -> 68-75ms

When testing Linkedlist vs the arraylist, adding and removing from a linked list took a lot let time than the array list.
But when it came to accessing the lists, the arraylist was lot better than the linked list


