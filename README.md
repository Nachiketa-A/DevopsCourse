# DevopsCourse
## Linux Fundamentals

### Linux(operating system)
Linux is an open source. It allows multiuser and multitasking with powerfull shell and multiple flavors/multiple linux types(Eg:ubuntu, redhat,fedora,kali linux,etc).
Allows high security doesn't need any anti-virus softwares.Linux is used by 91% of applications on the internet.
### Linux Architecture
<img width="270" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/974312b5-ad14-40f9-bf89-bb59a3acdef4">

Kernel: Kernel is a heart of linux.

Shell: Shell is the doorway from which user can interact with kernel and kernel  can interact  with  hardware.

We can directly work with the shell or we can connect the shell with applications and utilities.

In simple terms:- We install applications and utilities and to use this we write some commands through shell and then shell interact
                  with kernel then kernel interact with hardware.

## Linux commands
To check present working directory: pwd

To create a directory/folder: mkdir directory-name

To list directory name: ls

To see files and folders: ls -l

To check current loggedin user: whoami

<img width="299" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/27eae193-7e30-4926-b66c-422cde596f41">


To get back from directory: cd ..

To check which tools are installed on system:cd/bin   $bin: ls

To get logs: cd var  $var: cd log

<img width="853" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/60cff883-69a5-47a2-860b-b27e67708352">

To get `back to home: cd ~

To create a file in Linux: touch filename.txt

To type directly on terminal: echo "type text"

To check for data in file: cat file name

To write something in file: echo "type text" > file name

<img width="487" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/a4aefdd9-11fc-41fe-a0a2-62f583a6037b">

To create a file in particular folder: cd foldername/

To move file in folder: mv filename foldername

<img width="383" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/9196f7af-adc9-4958-833a-c4b1a0e5034e">

To check all commands used: history

When we start linux linux get boot so all start up files are in boot, command for that is:cd boot/   $boot:ls

<img width="507" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/acf8b18f-7c80-410b-8f7c-fc53f9bfb3e0">

### We can create a multiple folder and multiple files at a same time using a same commands

<img width="474" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/eb289a24-930d-4968-b536-7d9f0f882b61">

### We can also create a multiple folder and multiple files using loop

<img width="897" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/3f9bbb91-31d7-409d-8666-bb452f5b4978">


To give a path in particular folder: mkdir -p folder-name/folder-name/folder-name


<img width="655" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/30ed2f42-5bab-4ae6-b5ab-77c51298f112">


To get the name of the kernel: uname

To get the version of the kernel: uname-r

<img width="481" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/74346f6e-4b95-412c-86d2-690c1a0dc914">

To remove all txt file: rm file`name*.txt

To remove all folders: rm -r foldername*

To rename a folder: mv old-folder-name new-folder-name

<img width="694" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/89b43f3b-458e-4aff-84d7-2c25b9585f44">

To copy from one folder to another: cp -r source-folder-name/destination-folder-name/

To copy the content from folder to other one: cp -r copy-folder-name/* destination-folder-name/

<img width="567" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/f13b0f27-9c69-4b6a-915a-c4468b99764c">

## How to add new user in Linux

### We cannot simply add the new user only superuser can add the new one

To add user: sudo useradd username

To create a folder of already added user: sudo mkdir username

<img width="335" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/5368e255-410c-428a-9629-4bcf0aa52555">


To add user and also need to create a folder of an user: sudo useradd -m username

<img width="512" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/62b87d48-e353-4f6d-bf25-0056c1c8df16">

### To access a new user we need to create a password

To create a password for new user: sudo passwd username

To switch the user: su username

To get back to previous user: exit

<img width="466" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/8b74a999-e41b-4ac0-86e4-9f3e8cbc6343">

To see details of file,directory or folder: ls -la

### Permission details:

  **          **    user         other**
                  |            |
       **d       rwx   rwx    rwx
         |              |
     file type       group**

r:read
w:write
x:execute

To view an hidden file: ls -a

<img width="442" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/abecd8f6-f0bb-4cf0-9c3b-f6d91336b400">






























