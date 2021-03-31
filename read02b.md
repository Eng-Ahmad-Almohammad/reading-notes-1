|#|Description|
|---|---|
|read1|Prerequisites Version Control|
|read2|History Of Git Getting Started|
|read3|Setting Up A Git Repository|
|read4|Workflow|
|read5|Remote Repositories|

* # Read1
1. Local Version Control: A Local VCS entails one database on your hard disk that stores changes to files.

2. Centralized Version Control: The need for collaboration within a developer team on a single file or set of files led to the advent of the Centralized Version Control System (CVCS). This system entails a single server storing all changes and file versions, which can be accessed by various clients. 

3. Distributed Version Control:A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure. If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions. Also, in the event of corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines.

4. So, what is Git?
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.


* # Read2
1. Download Git 
 For MacOs: [MacOs](http://git-scm.com/download/mac)
 For Windows: [Windows](https://desktop.github.com/)
 For Linux: from Ubuntu [$ sudo apt-get install git] or
  [Linux](http://git-scm.com/download/linux)

2. Graphical Clients: Git includes inherent Graphical User Interface (GUI) tools. However, users can also utilize third-party tools created for particular platforms.
[Graphical Clients](https://git-scm.com/downloads/guis)

3. Initial Customization: After making sure Git has been installed, you should perform some customization steps, which should only need to be completed once on any machine. 
* Configuration of variables
* Identity Settings

4. Default Text Editor: Without configuration of a default text editor, Git will use the system’s default editor–most likely Vim. To configure a different text editor, such as Emacs, type the following into your Terminal or Command Line:
[$ git config --global core.editor emacs]

5. Check Settings:To check settings, use the [git config --list] command.

6. Getting Help: 
[git help command]
[git command --help]
[man git-command]


* # Read3
1. Importing: To import an existing project or directory into Git.
   1. Switch to the target project’s directory.
   2. Use the git init command.[$ git init]
   3. To start tracking these repository files, perform an initial commit by typing the following.
   [$ git add *.c]
   [$ git add LICENSE]
   [$ git commit -m “any message here”]

2. Cloning: You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL.
[$ git clone https://github.com/test]


* # Read4
1. Local Repository Structure: The local Git repository has three components:
   1. Working Directory: The actual files reside here.
   2. Index: The area used for staging
   3. Head: Points to the most recent commit

2. Saving Changes:
* Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.
* Untracked files were not in the last snapshot and do not currently reside in the staging area.

3. The Lifecycle of File Status
* After you edit a file, Git flags it as modified because of changes made after the previous commit.
* You stage the modified file.
* Then, you commit staged changes.

4. Check File Status: Using Command [$ git status]

5. Tracking and Staging A New File: 
Single file: [git add filename]
All files: [$ git add *]

6. Committing A File: Using Command [$ git commit -m “made change x,y,z”]

7. Committing All Changes: Using Command [$ git commit -a]

8. Pushing Changes: Using Command [$ git push origin master]

9. Stashing Changes: Using Command [git slash] [git slash apply]
* # Read5
1. Cloned Repositories: Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local branch.

2. Seeing Your Remote: 
For short names: git remote 
For all names: git remote -v

