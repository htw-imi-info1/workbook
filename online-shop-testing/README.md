online-shop-testing
===================

A project to practice unit testing.

Exercises
---------

_The practice exercise with the Number 9.x17 does not reference any exercise from the book, the others reference the numbers from Objects First with Java, 6th Edition listed below._

**9.15** Create a test to check that addComment returns false when a comment from the same author already exists. 

**9.16** Create a test that performs negative testing on the boundaries of the rating range. That is, test the values 0 and 6 as a rating (the values just outside the legal range). We expect these to return false, so assert false in the result dialog. You will notice that one of these actually (incorrectly) returns true. This is the bug we uncovered earlier in manual testing. Make sure that you assert false anyway. The assertion states the expected result, not the actual result.

**9.x17** If you find any bugs try to find the cause of the bug with a manual walkthrough and try to fix it.

**9.19** Create tests for SalesItem that test whether the findMostHelpfulComment method works as expected. Note that this method returns a ­Comment object. During your testing, you can use the Get button in the method result dialog to get the result object onto the object bench, which then allows you to make further method calls and add assertions for this ­object.­ This ­allows ­you ­to ­identify ­the ­comment ­object ­returned­ (e.g.,  by­ checking ­its­ author).­ You­ can ­also­ assert ­that ­the­ result­ is ­null or not null, depending on what you expect.



Original Readme
---------------
Project: online-shop-junit
Authors: Michael Kölling and David J. Barnes

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Sixth edition
   David J. Barnes and Michael Kölling
   Pearson Education, 2016

This project implements a small part of an online sales system (such as Amazon.com).
The current project is concerned only with customer comments for sales items. It contains
code to create, store, show and manipulate customer comments.

The purpose of this project is to introduce regression testing using JUnit. It includes
a test class that demonstrates some of the testing functionality. Testing is further
discussed in the book.

NOTE: There are several serious errors to be found in these classes.
