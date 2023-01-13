
# Class 3 Notes - revisions and the cloud

## Git Intro ##

Source: [https://blog.udemy.com/git-tutorial-a-comprehensive-guide/](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

### Version Control ###

Version control allows you to revisit various versions of a file or set of files by recording changes made. You can revert a file, track modifications and the people who did the modifying, and compare changes through version control. Mistakes can be easily fixed through a Version Control System (VCS).

* **Local Version Control**: entails one database on your hard disk that stores changes to files.

* **Centralized Version Control**: CVCS = centralized version control system, developed because of collaboration on developer teams on a single file or set of files.
- single server system storing all changes and file versions; can be accessed by various clients

* **Distributed Version Control** DVCS Distrubuted Version Control System addresses the server as a single point of failure; allows clients to create mirrored repositories. These data backups can be easily placed on the server to replace any lost info.
- bypasses issues with a single CVS going down, corruption of a central hard disk, etc.

* **What is Git?**
- Snapshots: Git is a DVCS that stores data in a file system made up of snapshots.
- Local Operations: Git mostly relies on local operations because most info can be found in local resoures. This allows for expediency.
- Tracking Changes: Every change is tracked by Git; Git detects file corruption or loss of info in transit.
- Loss of Data: Git minimizes the possibility of irreversible damage to files.
- States:
    - committed: data securely stored in a local database
    - modified: file has been changed but not committed to the database
    - staged: flagged a file's changed version to be committed in the next snapshot.

### History of Git ###
 Git comes from the open source software project Linux kernel. Linus Torvalds began creating Git after Linux kernel developers stopped using a DVCS called BitKeeper in 2005. The goal was to achieve non-linear development via multiple branches, that could support large projects, had strong anti-corruption mechanisms, and simmple design. 


### Getting Started ###
* **Download Git**
1. install as a package
2. install via another installer
3. download and compile the source code

### Mac OS X ##

* **Terminal**
* **Git Website**
* **GitHub**


### Windows ###
* **Git Website**
* **GitHub**

### Linux ###
* **Package Manager**
* **Git Website**

* **Graphical Clients**
- Git includes inherent GUI graphical user interface tools, but you can use third-party tools created for particular platforms.

* **Initial Customization**
- configuration of variables
- identity setting

* **Default text editor**
- without configuration of a default text editor, Git will use the system's default editor.

* **Check Settings**
To check settings, use the 'git config --list' command

* **Getting Help**
To get help, use these commands:
- 'git help command'
- 'git command --help'
- 'man git-command' 

### Setting up a Git Repository ###

* **Importing**
To import an existing project or directory:
1. switch to the target project's directory
2. use the git init command
3. perform an initial commit

* **Cloning**
You can create a copy of an existing Git repository by using the clone command with the repository's URL

### Workflow ###

* **Local Repository Structure**: The local Git repository has 3 components:
1. Working directory (the files reside here)
2. Index (area used for staging)
3. Head (points to the most recent commit)

* **Saving Changes**: 
1. Tracked files can be modified, unmodified, or staged
2. Untracked files were not in the last snapshot and don't reside in the staging area

* **The Life Cycle of File Status**
1. After you edit a file, Git flags the file as modified because of changes after the previous commit.
2. You stage the modified file.
3. You commit the staged changes.

* **Check File Status**: use the 'git status' command

* **Tracking and Staging a New File**
1. Single file = track one file with 'git add filename'
2. All files = track all files in a repository with 'git add *'

* **Committing a File**: after staging files, commit using the 'git commit -m "made change xyz"' command

* **Comitting All Changes**: 'git commit -a' commits a snapshot of all modifications to tracked files int he working directory.

* **Pushing Changes**: Next, push changes to a remote repository via 'git push origin master'

* **Stashing Changes**: when not ready to commit changes, 'git statsh' temporarily removes changes and hides them, giving you a clean working directory. When ready to continue working on the cahnges, 'git stash apply' command retrieves the hidden changes.

### Remote Repositories ###
Collaboration on Git projects requires remote repositories - versions of a project residing online or on a network.

* **Cloned Repositories**: for cloned repositories, Git will automatically give the name "origin" to the server from which you cloned and the name "master" to your local branch.

---------------------------------------------

## Things I Want To Know More About ##

Nothing at this time. 

URL: [https://s-glass.github.io/reading-notes/102/class3notes](https://s-glass.github.io/reading-notes/102/class3notes)