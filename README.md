# Java ArrayIndexOutOfBoundsException Bug
This repository demonstrates a common error in Java programming: the ArrayIndexOutOfBoundsException. This exception occurs when you try to access an array element using an index that is either negative or greater than or equal to the array's length.

The `bug.java` file contains the buggy code. The `bugSolution.java` file provides a corrected version.

## Bug Description
The bug in `bug.java` arises from attempting to access `arr[5]` in an array of size 5.  Valid indices for this array are 0 through 4. Attempting to access `arr[5]` results in an `ArrayIndexOutOfBoundsException`.

## Solution
The corrected code in `bugSolution.java` carefully checks the index before accessing the array element, preventing the exception.

## How to reproduce the bug
1. Compile `bug.java` using a Java compiler (javac bug.java).
2. Run the compiled code (java MyClass).
3. Observe the `ArrayIndexOutOfBoundsException`.

## How to run the solution
1. Compile `bugSolution.java` using a Java compiler (javac bugSolution.java).
2. Run the compiled code (java MyClassSolution).
3. Note that the program runs without errors.