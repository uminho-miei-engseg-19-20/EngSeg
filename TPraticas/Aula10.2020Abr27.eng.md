# TP  Class Assignment - 27/Apr/2020


Each group must answer the questions of the following exercises in the Github area of their group until the end of 04/May/2020\. For each day of delay, 0.15 points will be deducted from the grade of this assignment.

Note that these exercises should be done in the virtual machine provided.

## Exercises


### 1\. Integer vulnerability

Save the files in the directory [Aula 10](Aula10) into your local machine.


#### Experience 1.1

Use the IntegerCheck.java program to check the maximum and minimum values of the various integers on your machine.

+ How many bits does each of the integers have?


#### Experience 1.2

Test the IntegerError.java program and check what happens in _integer overflow_ situation.

+ Test with other integer types: byte, short, long

+ What if you need to use larger integers?

#### Experience 1.3

Test the IntegerCheck2.java program and enter correct and incorrect values.

+ What happens when you read a long and assign it to another type of integer?
+ What would happen if I used the scan for the correct type in each case (nextByte (), nextInt (), ...)?

#### Question P1.1

Review the overflow.c program.

1. What is the vulnerability that exists in the _vulneravel()_ function and what are the effects of it?
2. Complete _main()_ to demonstrate this vulnerability.
3. When running does it give some error? Which?


#### Question P1.2

Review the underflow.c program.

1. What is the vulnerability that exists in the _vulneravel()_ function and what are the effects of it?
2. Complete _main()_ to demonstrate this vulnerability.
3. When running does it give some error? Which?
4. Use the various defensive programming techniques seen in the theoretical class to mitigate the vulnerabilities.
    + 4.1 Explain the changes you've made.

#### Experience 1.4

Review the erro_sinal.c program.

1. What is the vulnerability that exists in the _vulneravel()_ function and what are the effects of it?
2. Complete _main()_ to demonstrate this vulnerability.
3. When running does it give some error? Which?


#### Experience 1.5

Review the y2k38.c program.

1. Compile and run it. From the result obtained, what can you say about the architecture where it was compiled? Why?
2. Compile it again with gcc's `-m32` option. What is the result? Why?

In question 2, if you are unable to compile, you have to install the gcc _multilib_ library. On the virtual machine use the following command:
> sudo apt-get install gcc-multilib

