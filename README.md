# Version-Control
Git and GitHub

# Types of Version Control
* 1-> Localized VC
* 2-> Centralized VC
* 3-> Distributed VC

 ## Localized VC
 --> Locally on the computer
 
 --> Locally on our laptop
 * Challenges
 1-> Hardware Crash
   
 2-> Power failures
 
 3-> Motherboard Crashes
 
 Laptop/Coumputer khrab huaa yaha lost hou gya toh sab khatam hou jayega


 ## Centralized VC
 --> Makes copies remotely 
 * Challenges
 1-> Single-point failure
 if the Central server is corrupted then all systems down

 ## Distributed VC
 --> No single point of failure

 # Version Control Tool
 * GIT
 * Bitbucket
 * Gitlab

 ## Git
 --> Distributed version control system

 *Git Snapshot*
 State of the project/code at a given moment.


### Git States
1- Modified
2- Staged
3- Committed

# Commands
1-> git --version

2-> git config --global user.email "abc@gmail.com"

3-> git config --global user.name "ABC"

*Check* 
4-> git config user.name

--->  git init

###  Add Track file 
--> git add .

--> git status

### Commit
--> git commit -m "my first commit"


#### Changes
1-> git add .
2-> git commit -m "message"



### See all previous commit
-> git log

=========================================

***latest commit is known as Head***


### Undo all the changes done
--> git restore file1.txt
**but used this command before git add .**

git restore --staged file1.txt

another command

--> git reset
==============================================

#Brances
it's a pointer that points to a snapshot

--> git branch

--> git branch new_branch

--> git checkout new_branch

--> git checkout -b branch2

* rename of branch
--> git branch -m branch2_renamed

* delete the branch
  --> git branch -d brach2_renamed


  # git Stash
  if you don't want to commit but want a saved file
  --> git add .

  --> git stash

