## JENKINS FUNDAMENTALS

Jenkins is a tool which helps in doing CI/CD.Jenkins is a tool which is build in Java.

For installation: (Jenkins LTS ubuntu install)

<img width="386" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/2ee3e9bd-cf0c-41da-bfe9-86a41900e97f">

#### What is CI?

CI stands for **Continuous Integration**.

In continuous Integration first code is get uploaded on any platform like github after uploading it on github code get run on runtime environment like docker,kuberntes,etc

(based on company) and tested with varoius test cases

on particular tool/framework this process runs continuously and if all test cases passed successfully then we can say CI process is passed.

#### What is CD?

CD stands for **Continuous Deployment**.

After CI build which we called an Artifact gets uploaded on **Docker Hub** and get deploy.

**Continuous Delivery**
When CD process have to done manually we called it as Continuous Delivery it depends on client requiremnets.

<img width="552" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/c1979d55-436f-4a08-b26f-d9138bceaba2">

### What is DEvSEcops?

Basically when security gets added in Devops we called it as Devsecops.

**OWASP**: security scanner tool

In DEvsecops CI process  before running the test cases code get scan and security check and after build is completed then again it get scan and if everything is runnung well

then it get uploaded on docker  hub and get deploy.


<img width="545" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/c1bd8bd3-31bd-4478-9798-c5db43e93962">

### Commands

**Jenkins run on port 8080**

To check java is installed or not : java --version

To check location of Java file: which java

To check Jenkins is active or not: systemctl status jenkins

