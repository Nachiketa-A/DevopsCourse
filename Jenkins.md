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

To print something in shell scripting: echo "Text"

To build code using docker: docker build . -t file_name:latest

To remove docker build images : docker rmi image_name

To start jenkins automatically : sudo systemctl enable jenkins

docker-compose up -d
**Pipeline** Orchestrates long-running activities that can span multiple build agents. Suitable for building pipelines(formerly known as workflows) and/or organizing complex activities that do not easily fit in free-style job type.

**Declarative Pipeline** We create declaractive pipeline using particular syntax like groovy scripting.

## Groovy Scripting

<img width="436" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/404bf867-823f-47ed-be15-46ec65da5861">


<img width="303" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/bd8de351-cf99-4247-916b-d84d69216cae">

#### Groovy Script for CI/CD Pipeline with permissions:


<img width="573" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/224bb11b-513b-4596-bd6f-d90ad6e1f1a7">

<img width="558" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/4323718f-abb8-49bd-bd90-74aa09ed4d76">


<img width="553" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/627f1134-2492-411c-8bfe-a7b76cdb7ad1">




**Credentials Binding**

**QUIZ**


**Q.Which plugin in Jenkins is essential to integrate version control systems like Git?**
  A : Git Plugin

**Q.Which file in a Jenkins project defines the build pipeline?**
  A : Jenkinsfile

**Q.Which scripting language is primarily used to define the structure and flow of Jenkins Declarative and Scripted Pipelines?**
  A : Groovy

**Q.Which of the following triggers a Jenkins job automatically when there is a code change in the source code repository?**
  A : SCM Polling

**Q.Which Jenkins feature allows for the temporary storage of secure environment variables, credentials amd other sensitive data, which can be accessed within a Jenkins pipeline?**
  A : Jenkins credentials Binding

**Q.Which plugin in Jenkins helps in checking the code quality?**
  A : SonarQube Plugin

**Q.Which directive in decalarative pipeline specifies where the pipeline should run?**
  A : Agent

**Q.What is blue ocean in Jenkins?**
  A : A personalised and modern GUI for Jenkins.

**Q.In Jenkins, a_______ is a series of task to be executed.**
  A : Job

**Q.If a Jenkins master fails, which of the following can directly take over job execution?**
  A : None

**Q.The primary reason reason to set up slaves in Jenkins is to**
  A : offload
  

### Jenkins Installation

step 1: Install Java

![image](https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/438355c7-2f1e-4051-818e-8c89272064ae)



![image](https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/2fb06172-7905-4140-bbe7-bd748a5f2ea9)


step 2: install JEnkins

![image](https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/e9d0ada0-3d8d-40e7-8cbf-ca6797cad1c6)






