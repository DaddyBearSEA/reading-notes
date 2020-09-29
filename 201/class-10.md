# Debugging


#### From the Duckett JS book: pg 449 - 486

## JavaScript book, Ch. 10, “Error Handling & Debugging”

## if you understand execution contexts (which have two stage) and stacks, you are more likely to find the error in your code
 > JS can be hard to learn and everyone makes mistakes when writing it. Learn how to find the errors in your code.  It will also teach you how to write scipts that deal with otential errors gracefully

## Debugging is the process of finding errors.  It involves a process of deductions

- The Console and Dev TOOLS
- Common Problems - what are the common sources of errors and how to solve them
- Handling Errors - how to code can deal with potential errors gracefully

1. knowing the order of execution
1. execution context
1. execution context & hoisting
1. understanding scope
1. understanding errors
1. error objects

Debugging Workflow - TA's follow this pretty well
> Debugging is about deduction:  Eliminating potential causes of an error. 
- Where is the problem?
- What exactly is the problem?
- What tools are installed to use?
- Console Logs
- breakpoints pg 476
- stepping through code
- Try, Catch, finally
- Throwing Errors



## The console helps narrow down the area in which the error is located, so you can try to find the exact error
<img src="images/errorofjscode.PNG">

This happened today in the Forms Workshop. Due to not have constrictors setup yet, this JS code was erroring out and not my code. Always look at the file where the error is coming from.


## JS has 7 diffent types of errors, Each creates its own error object, which can tell you its line number and gives a description of the error


## if you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. use them to give your users helpful feeback

Debugging Tips
1. Another Browser
1. Add Numbers
1. strip it back
1. Explaining the code to someone else
1. Search - Google
1. Code Playgrounds
1. Validation tools

Here are some common errors
1. Go back to Basics
1. Missed / Estra Characters
1. Data type issues.

[go back](../README.md)