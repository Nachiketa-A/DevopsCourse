# GIT(Global Information Tracker)

Git is version control system.

There are two types of version control system(VCS)

1.Distributed VCS : Example of DVCS is GIThub

2.Centralized VCS : Example Banking domain 

To make repository on linux: git init

After entering this command one .git hidden folder gets created

To know the status of created file in git via linux: git status

To staged the file :git add filename.txt

To unstage the file: git rm -- cached filename.txt or git restore --staged filename.txt

To commit: git commit -m "Message"

To restore the file: git restore filename.txt

When we modify any file using git the changes remain unstaged so we again need to staged that file

To get logs/history in git: git log(It wil show all the commits)


### Set global username and email for Git (Locally).

git config --global user.name "<your username>"

git config --global user.email "<your email>"

### Initialise an empty Git Repository

git init

### Clone an existing Git Repository

git clone <repository URL>

### Add file/stage to git

git add <filename>

### Add all the files to git

git add .

### Commit all the staged files to git

git commit -m "<your commit message>"

### Restore the file from being modified to Tracked

git restore <filename>
git checkout <filename>
### To get new branch

git checkout -b <filename>


### Show the status of your Git respository

git status

### Show the branches of your git repository

git branch

### Checkout to a new branch

git checkout -b <branch name>


### Checkout to an existing branch

git checkout <branch name>

### Remove a branch from Git

git branch -d <branch name>

### Show remote origin URL

git remote -v

### Add remote origin URL

git remote add origin <your remote git URL>

### Remove remote origin URL

git remote remove origin 


### Fetch all the remote branches

git fetch

### Push your local changes to remote branch

git push origin <branch name>

### Pull your remote changes to local branch

git pull origin <branch name>

### Check you git commits and logs

git log

## If we use https to clone then we need to use https protocols for clone we can also clone through SSH.

## To clone the repository using SSH we need to generate a key

### To generate a key for SSh : ssh-keygen

There will be 2 keys one is public key and another one is private key

### We will enter public key on the repository where we need to connect. 





