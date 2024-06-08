### Ansible Concepts: Playbook, Play, Modules, Tasks, and Collections

#### Playbook

A Playbook is a YAML file that defines a series of actions to be executed on managed nodes. It contains one or more "plays" that map groups of hosts to roles.

#### Example

![image](https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/342f0360-5cc0-415f-a167-3e2d1b4f5dfa)


#### Play

A Play is a single, complete execution unit within a playbook. It specifies which hosts to target and what tasks to execute on those hosts.

Plays are used to group related tasks and execute them in a specific order.

![image](https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/867883ae-2a4a-4e8a-822f-cb309a662169)


#### Modules

Modules are the building blocks of Ansible tasks. They are small programs that perform a specific action on a managed node, such as installing a package, copying a file,

or managing services. 

Example

![image](https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/66ec7002-9b6a-4383-9ebe-ff75a3adc90a)


#### Tasks

Tasks are individual actions within a play that use modules to perform operations on managed nodes. Each task is executed in order and can include conditionals,

loops, and handlers.

![image](https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/1f33ca71-39ad-4a64-bcd4-1215df90cde3)

