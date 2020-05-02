#  TP  Class Assignment - 04/05/2020

Each group must answer the questions of the following exercises in the Github area of their group until the end of 11/May/2020\. For each day of delay, 0.15 points will be deducted from the grade of this assignment.


**Note:**
Save the files in the directory [Aula 11](Aula11) to your local machine.

## Exercises


### 1\. Input validation

#### Experience 1.1

Analyze the InputValidation.cpp and InputValidation.java files.

1. Explain the two problems: (i) usage of cin/Scanner for reading, (ii) accessing the array

2. What would you change?


#### Experience 1.2

Analyze the file WhileEx.java.

1. What are the problems with the program input?

2. Change the program to validate all the input and recover gracefully from the errors.


#### Experience 1.3

Analyze the file Input.cpp.

1. What are the problems with the program input?

2. Change the program to validate all the input and recover gracefully from the errors.


#### Experience 1.4

Analyze the file Input.java.

1. What are the problems with the program input?

2. Change the program to validate all the input and recover gracefully from the errors.



#### Question P1.1

Analyze the program filetype.c that prints on the screen the file type of the argument (file path).

1. There are at least two types of vulnerabilities studied in the theoretical "Input Validation" class that can be exploited. Identify them.

2. Provide the code/steps/command line that allow to exploit each of the vulnerabilities identified in the previous question.

3. What would happen if your program had _setuid root_ permissions?


#### Experience 1.5

Analyze the program readfile.c that prints on the screen the contents of the filename passed as an argument - the suffix ".txt" is added to the filename to ensure that it only lets you read text files.

1. There is a vulnerability studied in the theoretical  "Input Validation" class (in conjunction with another that you have already studied) that allows the program to print files that do not end in ".txt". Explain.

2. Enter the command line required to access the _/etc/passwd_ file.


#### Experience 1.6

Analyze the file string_format.c with the format string vulnerability sample explained in the theoretical class, and the string_format2.c file without the vulnerability.

1. Experiment with multiple input values with both the vulnerable and the non-vulnerable program and draw your conclusions.

#### Experience 1.7

Test your ability to identify security issues during code review. Complete the OWASP Security Code Review 101 at <https://trendmicro.github.io/SecureCodingDojo/codereview101/>.

#### Experience 1.8

An important security strategy is "defense in depth". Explain what you think this means. How could this relate to input validation?


#### Question P1.2

Desenvolva um programa (na linguagem em que tiver mais experiência) que pede:

+ valor a pagar,
+ data de nascimento,
+ nome,
+ número de identificação fiscal (NIF),
+ número de identificação de cidadão (NIC),
+ numero de cartão de crédito, validade e CVC/CVV.

Valide esse input de acordo com as boas regras de validação de input, apresentadas na aula teórica.

Develop a program (in the language you have the most experience) that asks for:

+ amount to pay,
+ date of birth,
+ name,
+ tax identification number (VAT number),
+ citizen identification number (NIC),
+ credit card number, validity and CVC / CVV.

Validate the input according to the "responsible" validation rules, presented in the theoretical class.
