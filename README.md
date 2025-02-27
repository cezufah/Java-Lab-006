# Java-Lab-006

## PART 1
In this README.md, answer the following question:
* What happens if you invoke a value method and don't do anything with the returned result; that is, if you don't assign the returned result to a variable or use it as part of a larger expression?
    * nothing happens?
## PART 2
* Fork and clone this lab as you have done in all previous labs, and then complete the following:
    * Create a new class called Lab006
    * Create two integer instance variables for class Lab006 called n and m.
    * Create a **constructor** for class Lab006 that takes two integers, n and m and assigns them to Lab006 instance variables.
        * "takes two integers" means that the constructor method must have two parameters of the appropriate data type.
    * Write a public/instance method named, isDivisible, that references, instance variables n and m, and returns true if n is evenly divisible by m, and false otherwise.
        * Hint: remember that `x%2==0`, means that x is evenly divisible by 2.
    * In a static main method, prompt the user for two integers and store those values into local variables.
    * Use the local variables as the arguments to the Lab006 constructor when creating a new Lab006 object.
    * Call isDivisible using a Lab006 object, and be sure to have code that "handles" the returned value from isDivisible.
        * Use one of the "handling" techniques as demonstrated at the top of pg 86 or on pg 93 of ThinkJava as a reference for how to handle a returned value.
    * Use a print command to display an appropriate label and the result of isDivisible.

## PART 3
* Add javadocs to your code Including programmer identifying comments at the top of your class, and javadoc definitions for your methods and parameters.

## PART 4

* Make sure to use the Git tab at the bottom of IntelliJ to create a Fall_2022 feature branch
* Commit and Push your running code back to your GitHub account
* Issue a Pull request back to my Java-Assignment-006 repo
* Cut and Paste the Pull request URL into your Canvas assignment to turn it in.
