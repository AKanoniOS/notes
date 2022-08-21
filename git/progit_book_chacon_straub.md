# 1 Getting Started
We're going to look at...
* The History of Version Control Systems
* A Short History of Git

## 1.1 Getting Started - About Version Control
* Git is a Version Control System (VCS)
* Fancy save button!!

Programmers developed local VCSs that had a database that stored all the changes to files for **revision control**.  

Programmers now have revision control, which is great, but what if they want to collaborate with other programmers on versions, or store versions off their machine? Enter **centralized VCSs** - servers that your Version Control System saves to.

...but we still have a problem. What if the building the server is in *burns down*, then your versions are gone! Enter the shift from **centralized VCSs** to **distributed VCSs**.

### Distributed VCSs
Distributed VCSs allow clients to *fully mirror* the repository. Thus, copying the full project and all of its version history.

## 1.2 Getting Started - A Short History of Git
* Linux Kernel - software changes passed around as patches and archived files. 
* Linux Kernel Community started using Proprietary DVCS called BitKeeper. 
* In 2005, relationship between company that owned BitKeeper and Linux Kernel community broke down, BitKeeper became a paid software. Linux Kernel community and Linus Torvalds, creator of Linux, develop new VCS
* Goals included
    * Speed
    * Simple Design
    * Strong support for non-linear development (thousands of parallel branches) 
    * Able to handle large projects efficiently

## 1.3 Getting Started - What is Git?
Git thinks about data like a *stream of snapshots*.
* If files haven't changed, git doesn't store the file again, but will refer back to the unchanged version.

Git operations are **local**.
* Git only needs local files and local resources to operate. 
    * Faster than pulling from a server
* You can work offline
    * Commit locally and push to GitHub once you have internet.

Git has **integrity**.
* You can't lose information without Git detecting it
    * Everything is Checksummed
* Git uses SHA-1 hashes to store information

Git generally only adds data, so it makes it hard to lose something.

## The Three Stages
Git has **three** stages that your files can reside in:
1. Modified
2. Staged
3. Commited

"Saved" git files are *commited* to the git repository. When you change them they become *modified*. Once they are modified, you need to add them to be *staged* for the next commit to the repo. 
* (modify) one rocketship, (stage) the rocketship by adding it to the launchpad, (commit) the rocketship by launching it to the repo

1. Checkout the project from the repo
2. Stage fixes from your working directory
3. Commit from the staging area to the repo

## 1.4 Getting Started - The Command Line
The Unix Command Line Interface uses a language called BASH. You navigate your directories and interact with your files through the CLI. Basic BASH commands that I use all the time include:

* ```cd``` - change directory
* ```cd .. ``` - change directory to parent directory
* ```ls``` - list files and directories in current directory
* ```mkdir``` - make directory
* ```touch``` - make file
* ```mv``` - move or rename files & directories
* ```rm``` - delete files
* ```rm -r ```- remove directory

This is all done through the terminal on Unix machines. All git commands are run through the CLI. 

# 2 Git Basics
## 2.1 Git Basics - Getting a Git Repository
You can get a repo one of two ways:
1. You can turn a local repo into a Version Controlled Git Repository
2. ** You can clone an existing repo (better way)

### Initializing local repo
* Navigate to directory
* Initialize it with 
    ```
        git init
    ```
### Clone Existing Repo
Navigate to the directory where you want to store your repo, make the repo on GitHub, hit clone button, copy SSH key paste into following command:
```
    git clone *ssh key here*
```

## 2.1 Git Basics - 
## 2.1 Git Basics - 
## 2.1 Git Basics - 
## 2.1 Git Basics - 
## 2.1 Git Basics - 
