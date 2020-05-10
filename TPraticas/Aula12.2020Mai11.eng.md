# TP  Class Assignment - 11/May/2020


Each group must answer the questions of the following exercises in the Github area of their group until the end of 25/May/2020\. For each day of delay, 0.15 points will be deducted from the grade of this assignment.

Note that these exercises should be done in the virtual machine provided.



**_WebGoat_ installation instructions, for those who do not use the available virtual machine:**

In this lesson we will use a **WebGoat** Docker image. **WebGoat** is a deliberately insecure Web application maintained by OWASP, which is intended to be a complement to Web application security classes, and therefore contains common application failures.

You can install Docker directly on your computer's operating system.

If you want **to install docker on your computer** follow the instructions at https://store.docker.com/search?type=edition&offering=community for your operating system.

If your computer's operating system is the same as the virtual machine, follow the instructions below to install docker:

1. `sudo apt-get update`

2. `sudo apt-get install apt-transport-https ca-certificates curl gnupg2 software-properties-common`

3. `curl -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-key add -`

4. `sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/debian  $(lsb_release -cs) stable"`

5. `sudo apt-get update`

6. `sudo apt-get install docker-ce`


----

**Note:** Whenever in the exercises below you are asked to use **WebGoat**, you must perform the following steps:

1. Ensure that you have already installed docker on your computer or virtual machine.

2. Obtain version 8.0 of WebGoat, through the command `sudo docker pull webgoat/webgoat-8.0`

3. Boot WebGoat with the `sudo docker run -p 8080:8080 -t webgoat/webgoat-8.0` command.

     Note that WebGoat takes 30 - 50 seconds to start up, having started when a line appears on the screen containing the following information `INFO: Started StartWebGoat`

5. In the virtual machine Firefox access http://localhost:8080/WebGoat.


At the end, to stop docker and WebGoat, you should make the following commands:

+ `sudo docker ps` to get the Container ID
+ `sudo docker kill <Container ID>` where `<Container ID>` is the value indicated in the previous command.


----


## Exercises


### 1\. _Injection_

#### Experience 1.1

Go to https://free.codebashing.com/courses/java and follow the _SQL Injection_ example.


#### Experience 1.2

Go to https://free.codebashing.com/courses/dotnet and follow the _XXE Processing_ example.


#### Question 1.1 - _SQL Injection_

In WebGoat follow the lesson _(A1) Injection > SQL Injection (jntro)_.

In all steps try first to solve without help. If you get to a point where you can not move forward, use "Show Hints" for help. 




### 2\. XSS

#### Experience 2.1

Goto https://free.codebashing.com/courses/nodejs and follow the _Persistent (Stored) XSS_ example.

#### Question 2.1 - _XSS_

In WebGoat follow the lesson _(A7) Cross-site Scripting_.

In all steps try first to solve without help. If you get to a point where you can not move forward, use "Show Hints" for help. 



### 3\. Broken Authentication

#### Question 3.1 - _Password Reset_

In WebGoat follow the lesson _(A2) Broken Authentication > Password Reset_.

In all steps try first to solve without help. If you get to a point where you can not move forward, use "Show Hints" for help. 

### 4\. Vulnerable components

#### Question 4.1 - _Vulnerable components_

In WebGoat follow the lesson _(A9) Vulnerable Components_.

In all steps try first to solve without help. If you get to a point where you can not move forward, use "Show Hints" for help. 

