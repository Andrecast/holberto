
# Vagrant


## Concepts

_For this project, students are expected to look at these concepts:_

-   [Source code management](https://intranet.hbtn.io/concepts/22)
-   [Using Vagrant on the Holberton computers](https://intranet.hbtn.io/concepts/53)
-   [Git and Github cheat sheet - Everything in less than 30 seconds](https://intranet.hbtn.io/concepts/57)
-   [The Framework](https://intranet.hbtn.io/concepts/75)
-   [Using Vagrant on your personal computer](https://intranet.hbtn.io/concepts/81)
-   [Approaching a Project](https://intranet.hbtn.io/concepts/350)

## Resources

**Read or watch**:

-   [Zero day](https://intranet.hbtn.io/rltoken/NcuS4-7zF9-edjbo157uQQ "Zero day")
-   [Virtual machine](https://intranet.hbtn.io/rltoken/v2RbeSrU14w3KTwbGYH3Fw "Virtual machine")
-   [man uname](https://intranet.hbtn.io/rltoken/3AHxDiZwhZwPM_GiHox0gQ "man uname")
-   [Resources to learn Git](https://intranet.hbtn.io/rltoken/ZrSQswLIJ9OTQsbPe7t7Kg "Resources to learn Git")
-   [About READMEs](https://intranet.hbtn.io/rltoken/ry46rhDKOUNilNK09uWXWg "About READMEs")
-   [How to write a Git commit message](https://intranet.hbtn.io/rltoken/GVFbHgJXNQ4aliCLV6Lhxw "How to write a Git commit message")

## Learning Objectives

At the end of this project, you are expected to be able to  [explain to anyone](https://intranet.hbtn.io/rltoken/_qzmHNff9vaaeDBMkkIDHg "explain to anyone"),  **without the help of Google**:

### General

-   What is a zero-day
-   What is a virtual machine
-   What is Vagrant
-   Who wrote Vagrant
-   What is Ubuntu
-   What does “Ubuntu” mean
-   How to use VMs with Vagrant
-   What does the command  `uname`  do
-   What is source code management
-   What is Git
-   What is GitHub
-   What is the difference between Git and GitHub
-   How to create a repository
-   What is a README
-   How to write good READMEs
-   How to commit
-   How to write helpful commit messages
-   How to push code

## Requirements

### General

-   A  `README.md`  file at the root of the  `holbertonschool-zero_day`  repo, containing a description of the repository
-   A  `README.md`  file, at the root of the folder of  _this_  project (i.e.  `0x00-vagrant`), describing what this project is about

## More Info

### Install  `git`

If  `git`  is not already installed on your terminal:

```
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git

```

### Basic usage

At the end of this project you should be able to reproduce and understand these command lines:

```
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main

```

## Quiz questions

#### Question #0

What is a virtual machine?

-   A set of servers for software development
    
-   A system for developing virtual reality
    
x   An emulation of a computer system
    

#### Question #1

Ubuntu is a ____ distribution.

-   Windows
    
x   Linux
    
-   MacOS
    

#### Question #2

What is the difference between Git and GitHub?

x   Git is a version control tool; GitHub is an online service built around the Git tool
    
-   GitHub is a version control tool; Git is an online service built around the GitHub tool
    
-   There is no difference, they have the same functionality
    

#### Question #3

Which of the following is a helpful commit message?

-   “Fix code”
    
-   “Can someone review this commit?”
    
x   “Fix incorrect parsing of user input”
    

#### Question #4

You wrote your first script but it does not execute properly. In order to solve this problem, what’s the first thing you should do?

-   Ask a peer
    
-   Ask a TA
    
x   Read the documentation

## Tasks

### 0. Create and setup your Git and GitHub account

#advanced

Score:  100.00%  (Checks completed: 100.00%)

You will need Git for this project, you might have to  [install it](https://intranet.hbtn.io/rltoken/TJrA7MIEl9LxnkGNH_ddmw "install it")  on your computer if it’s not done yet.

-   Configure your basic info (name, email) on your local machine – they will be part of your commits.  [Tips](https://intranet.hbtn.io/rltoken/72jmwYpf2OeuoOn9XM3vQg "Tips")

On  [GitHub.com](https://intranet.hbtn.io/rltoken/m27bKy8K40cIkyHWQ36i2w "GitHub.com"):

-   Using the graphic interface on the website, create the repository (if it’s not done yet)
    -   Name:  `holbertonschool-zero_day`
    -   Description:  `I'm now a Holberton Student, this is my first repository as a full-stack engineer`
    -   Public repo
    -   No  `README`,  `.gitignore`, or license

On your computer, open a terminal and do the following:

-   Navigate to your home directory.  [Tips](https://intranet.hbtn.io/rltoken/-odz94uVNOsPV1ovYZLuyw "Tips")
-   Create a directory  `holbertonschool-zero_day`.  [Tips](https://intranet.hbtn.io/rltoken/AHYBfU0itf9qEiwLdiaVJw "Tips")
-   Navigate to this new directory.  [Tips](https://intranet.hbtn.io/rltoken/9g9c-qBPHWSGcpxbs69ASw "Tips")
-   Initialize git and add the remote origin
-   Create a file  `README.md`  with Emacs (or other command line editors) and write a small  [Markdown](https://intranet.hbtn.io/rltoken/Ru3ANLuzGs4g0v2qsN3efA "Markdown")  text to present this project.  **This file is mandatory in all Holberton School projects**
-   Add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin (Note: You will probably need to set your login/password to push to the remote server)

Good job!

You pushed your first file in your  **first repository**  of the  **first task**  of your  **first Holberton School project**.

**Repo:**

-   GitHub repository:  `holbertonschool-zero_day`
-   File:  `README.md`

Done!  Help  Re-check your code  Get a sandbox  QA Review

### 1. Hello Ubuntu

#advanced

Score:  100.00%  (Checks completed: 100.00%)

Inside the  `holbertonschool-zero_day`  repo, create a new directory called  `0x00-vagrant`. Add a  `README.md`  file to this directory.

`ssh`  into your Ubuntu VM. What does the command  `uname`  print when you run it without any option?

Type your answer into a file in the  `0x00-vagrant`  directory and push it to GitHub. Name your file accordingly as shown below.

**Repo:**

-   GitHub repository:  `holbertonschool-zero_day`
-   Directory:  `0x00-vagrant`
-   File:  `0-hello_ubuntu`

Done!  Help  Re-check your code  Get a sandbox  QA Review
