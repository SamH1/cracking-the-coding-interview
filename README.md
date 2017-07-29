## Cracking The Coding Interview Solutions with Automated Unit Tests
[![Coverage Status](https://coveralls.io/repos/github/alexhagiopol/cracking-the-coding-interview/badge.svg?branch=master)](https://coveralls.io/github/alexhagiopol/cracking-the-coding-interview?branch=master)

### Introduction
This repository contains solutions for Gayle Laakmann McDowell's [*Cracking the Coding Interview 6th Edition*](http://a.co/baneyGe). 
Admittedly, there are lots of other GitHub repos with solutions for this book. But when you're deeply confused, how do you 
know that their code actually works? You don't. That's why the #1 rule for this repo is 
that *every* solution must have one or more unit tests in `tests.py` using the Python [`unittest`](https://docs.python.org/3.6/library/unittest.html) 
framework. We enforce the unit tests using continuous integration via Travis CI and test coverage statistics via Coveralls.io. 
Take a look at the [test result reports](https://travis-ci.org/alexhagiopol/cracking-the-coding-interview) and 
[test coverage reports](https://coveralls.io/github/alexhagiopol/cracking-the-coding-interview). 

#### Running the Tests Locally:
In the root directory, execute the following to run all of the tests:
    
    python tests.py

#### Generating a Test Coverage Report Locally:
This will show exactly which lines are not covered in each file:

    conda install coverage
    coverage run --source=python_solutions tests.py
    coverage report -m

### Contributing
I need help on this project! PRs are very welcome. Here are some ways you can help:

1. Solving unsolved problems.
2. Improving existing solutions with better performance or clarity.
3. Adding more unit tests or refactoring to increase test coverage %.

### Completion Progress
#### Python Solutions:
1. Chapter 1 - Arrays and Strings: 9 / 9  complete.    
2. Chapter 2 - Linked Lists: 8 / 8 complete.   
3. Chapter 3 - Stacks and Queues: 6 / 6  complete.
4. Chapter 4 - Trees and Graphs: 11 / 12 complete.  
5. Chapter 5 - Bit Manipulation: 1 / 8  complete.
6. Chapter 8 - Recursion and Dynamic Programming: 1 / 12  complete.
7. Chapter 17 - Hard: 1 / 26 complete.