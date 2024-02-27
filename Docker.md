# Docker Fundamentals

-<img width="418" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/5f852d8d-fb2a-4d8d-950a-3e20e33191d6">

### Docker works as a hypervisor.
Docker container will run Docker engine. Docker container contains everything except operating system.Docker takes operating system from Kernel which connects with Hardware.

To use Docker we need:
1. Docker File
2. Docker image
3. Docker container

<img width="505" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/1deec213-edee-429f-833d-73f43c466b3d">

Docker is a tool that performs OS level virtualization also known as Containerization.

## Architecture of Docker

<img width="476" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/ab1aacfe-5f3e-47fa-8800-dfba46369ee7">

### Components of Docker

**Docker Daemon**

Docker daemon runs on the host OS
It is responsible for running docker containers and ,managing docker services
Docker daemons can communicate with other daemons.

**Docker Client**

Docker users can interact with docker daemon through client
Docker uses command and Rest API to communicate with the docker daemon.
When client runs any server command on the docker client terminal the client terminal sends the docker command to the docker daemon.

**Docker Host**

Docker host is use to providing an environment to execute and run applications. It contains the docker daemon,images,containers,networks and storage.

**Docker Hub/Registry**

Docker Registry manages and stores the docker images.




## Hypervisor


To run Docker engine we need Hypervisor.
A hypervisor, also known as a virtual machine monitor or VMM, is software that creates and runs virtual machines (VMs). A hypervisor allows one host computer to support multiple guest VMs by virtually sharing its resources, such as memory and processing.

<img width="505" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/1153657e-a54e-4a96-bf0e-7ea12202fd03">
