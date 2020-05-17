# Engenharia de Segurança - Projects

As referred in the first class, the "Software development project" / "Research on a topic" is part of the evaluation of Engenharia de Segurança (worth 75% of the final grade), and consists of 3 projects to be delivered on the following dates:

- Project 1 – 23/03/2020
- Project 2 – **11/05/2020** (changed)
- Project 3 – 08/06/2020

These projects are done by a working group with a maximum of 3 elements.

The **project meetings** will take place whenever students request them (please send a prior email to book a meeting slot), on Mondays after the Engenharia de Segurança class.

There is also a *workspace* in  slack for use within the Engenharia de Segurança course.
To join, use the invitation 
https://join.slack.com/t/engenhariadeseguranca/shared_invite/enQtNTU1Mzk4MTc2NjE1LTc2NTExY2U5Y2RiNmZkY2I4MGFlOTZkZGMyMTEzZTc0Y2UzM2VhMTczZjU4ZWI5YzY4N2JiNWVhZjVmMTk1MDM



## 1. Project 1


Each group will carry out research on the topic of secure software development, being expected to deliver a written report at the end, as well as make an oral presentation (30 minutes) in class format. 

Depending on the number of your group, in order to carry out this project you should focus your attention on the following supporting documents:

+ Group 11 - [Principles for Software Assurance Assessment](https://safecode.org/wp-content/uploads/2015/11/SAFECode_Principles_for_Software_Assurance_Assessment.pdf)
+ Group 2 - [Fundamental Practices for Secure Software Development, Third Edition](https://safecode.org/wp-content/uploads/2018/03/SAFECode_Fundamental_Practices_for_Secure_Software_Development_March_2018.pdf)
+ Group 12 - [Software Security Takes a Champion](https://safecode.org/wp-content/uploads/2019/02/Security-Champions-2019-.pdf)
+ Group 1 and Group 3 - [Tactical Threat Modeling](https://safecode.org/wp-content/uploads/2017/05/SAFECode_TM_Whitepaper.pdf)
+ Group 4 and Group 5 - [Managing Security Risks Inherent in the Use of Third-party Components](https://safecode.org/wp-content/uploads/2017/05/SAFECode_TPC_Whitepaper.pdf)
+ Group 6 - [Practices for Secure Development of Cloud Applications](https://safecode.org/wp-content/uploads/2018/01/SAFECode_CSA_Cloud_Final1213.pdf)
+ Group 7 and Group 10 - [OWASP Proactive Controls](https://github.com/OWASP/CheatSheetSeries/blob/master/IndexProactiveControls.md)
+ Group 8 - [OWASP Mobile Application Security Verification Standard (MASVS)](https://mobile-security.gitbook.io/masvs/)
+ Group 9 - [OWASP Mobile Security Testing Guide (MSTG)](https://owasp.org/www-project-mobile-security-testing-guide/)
+ Group 13 - [Mitigating the Risk of Software Vulnerabilities by Adopting a Secure Software Development Framework (SSDF)](https://csrc.nist.gov/CSRC/media/Publications/white-paper/2019/06/07/mitigating-risk-of-software-vulnerabilities-with-ssdf/draft/documents/ssdf-for-mitigating-risk-of-software-vulns-draft.pdf)
+ Group 14 - [UC Secure Software Development Standard](https://security.ucop.edu/files/documents/policies/secure-software-development-standard.pdf)

## 2. Project 2

Each group will carry out research on software quality tools and / or software tests, being expected that in the end they will deliver a written report, as well as make an oral presentation (30 minutes) in class format. 

The work of the first 8 groups is carried out within the scope of code/software _quality indicators_, and may be based on the work of [The TIOBE Quality Indicator a pragmatic way of measuring code quality](https://www.tiobe.com/files/TIOBEQualityIndicator_v4_3.pdf):


> To obtain a systematic way of measuring and qualifying these measurements, the 8 most commonly used
> software code quality metrics in industry today have been selected that can be measured in an automated
> way. These are:
> 1. Code coverage
> 2. Abstract interpretation
> 3. Cyclomatic complexity
> 4. Compiler warnings
> 5. Coding standards
> 6. Code duplication
> 7. Fan out
> 8. Security 

The purpose of these first 8 groups is to explain what the analyzed software quality indicator is, what it is used for, what tools (you can find [here](https://www.tiobe.com/tics/fact-sheet/) some information, but it is expected that the report will also use other sources to present more and better tools) are used depending on the programming language, detailing open-source tools and presenting basic and advanced examples of their use.


+ Group 11 - *Code coverage* tools and techniques
+ Group 2 - *Abstract Interpretation* / * Deep Flow Analysis* tools and techniques
+ Group 12 - *Cyclomatic complexity* tools and techniques
+ Group 1 and Group 3 - *Compiler warnings* tools and techniques
+ Group 4 and Group 5 - *Coding standards* tools and techniques
+ Group 6 - *Code duplication* tools and techniques
+ Group 7 and Group 10 - *Fan out* tools and techniques
+ Group 8 - *Security* tools and techniques


Group 9 will analyze and explore the tools [OWASP Code Pulse](https://owasp.org/www-project-code-pulse/) and [OWASP ZAP](https://www.zaproxy.org/), presenting basic and advanced examples of its use.

Group 13  will analyze and explore the tools [Selenium](https://selenium.dev/), [Kritica](https://kritika.io/) and [Deepscan](https://deepscan.io/), presenting basic and advanced examples of its use.

Group 14  will analyze and explore Lint tools, namely the [ESLint](https://eslint.org/) for javascript, presenting basic and advanced examples of its use (including its integration with Visual Studio Code IDE).


## 3. Project 3

Based on what was learned as a result of Project 1 and Project 2 (and theoretical classes, namely classes about secure programming), each group will develop in a different programming language, a command line application (CLI) that allows testing the operations of the SCMD service (Signature CMD), *reverse engineering* the application [CMD-SOAP](https://github.com/devisefutures/CMD-SOAP).


+ Group 1 - C
+ Group 2 - Rust
+ Group 3 - Ruby
+ Group 4 - PHP
+ Group 5 - Java
+ Group 6 - Node
+ Group 7 - Go (Golang)
+ Group 8 - Swift
+ Group 9 - Perl
+ Group 10 - C++
+ Group 11 - React
+ Group 12 - Scala
+ Group 13 - D
+ Group 14 - Javascript

At the end, you must make the code and report available on github (or gitlab or similar), and make it explicit in the report:

+ Secure software development techniques you used, and how you applied them;
+ Tools and software quality indicators used, and results;
+ Way to test the developed code.
