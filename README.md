

## GitHub and Git Walk-Thru, from Soup to Nuts ...

### Prerequisites
1. Need to setup a GitHub user account (This is remote/web based account) 
2. Need to have git installed on at least 1 local machine.  There is a Github client but for learning purpose, I'll just be using git bash. I fell that a simple command line presents more clairy; there are enough ideas here to be mastered without introducing complications of a GUI.
3. Need to create a repository (either from you local machine git shell or from GitHub's web site.
4. Need to have D Languages, DMD and DUB installed on you local machine.
	

This is my first **markup** document. I am very _excited_. I mean **_Really Excited!_**

I just created a new text file named firstMarkdown.md on my desktop. Then  
 
To view, open this file on a Windows computer in your Chrome Browser, Use the command is `ctrl + o` and then you can choose the file. On a Mac use `command + o`.

Also had to add a google extension called **Markdown Preview Plus** in order for Chrome to display markdown documents. Also had to go into the extension and click on the _Allow access to file URLs_


## GitHub setup

1. First create an user account on GitHub's web site. My account's user is called *WhatMeWorry*

2. Create a new repository on GitHub. Login under your new account and...

    - In the upper-right corner of any page, click + icon, and then click New repository.
    - Type a short, memorable name for your repository.
	
        ```
        SoupToNuts
        ```
    - Optionally, add a description of your repository. ...
	
	    ```D 
		This repo documents the complete life cycle of a git/GitHub repository. 
	    Basically, a very detailed walk through.
        ```
    - Choose between creating a public or private repository. ...
    - Select [x] Initialize this repository with a README.
	
        ```
        This very text file firstMarkDown.md will become the README file.
        ```
    - Click Create repository.
	
        ```D
        All repositories created on GitHub are considered *remote*.
        ```
To become really useful, a local copy of the remote repository needs to be created on your computer with a *clone* command. Cloning also keeps local and remote repositories synchronized.

3. Open a Terminal Git Bash.

    - On windows open the Git Shell, Window's window is titled :/c/Users/kheaser/OneDrive for Business/GitHub
	- git shell's prompt is kheaser@IT-ASST-SB  ~/OneDrive for Business/GitHub $	

	- On GitHub, navigate to the main page of the repository.

    - At green Clone or download button, click "Clone or download."

    - Going back to the Terminal Bash Git, hange the current working directory to the location where you want the cloned directory to be made.

    - Type git clone, and then paste the URL you copied previously.
	
	    ```		
        $ git clone https://github.com/WhatMeWorry/SoupToNuts.git
        Cloning into 'SoupToNuts'...
        remote: Counting objects: 3, done.
        remote: Compressing objects: 100% (2/2), done.
        remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
        Unpacking objects: 100% (3/3), done.
		  
        kheaser@IT-ASST-SB  ~/OneDrive for Business/GitHub	
        $ ls
        Delivery/  SoupToNuts/
        $ ls -al
        total 5
        drwxr-xr-x 1 kheaser 1049089   0 May 19 14:47 ./
        drwxr-xr-x 1 kheaser 1049089   0 May 19 14:47 ../
        drwxr-xr-x 1 kheaser 1049089   0 May 19 14:47 .git/
        -rw-r--r-- 1 kheaser 1049089 128 May 19 14:47 README.md
		
        ```

	- At your local Windows computer, open git shell (aka git bash)
		
	    ```
        $ pwd
        /c/Users/kheaser/OneDrive for Business/GitHub
		$ ls
        SoupToNuts/
        ```
	
4. Change the current working directory to your local project created by previous clone command
	    ```
		$ cd SoupToNuts/
        kheaser@IT-ASST-SB  ~/OneDrive for Business/GitHub/SoupToNuts (master)
        ```

5. Initialize the local directory as a Git repository. (On)
```
https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/#platform-linux
```
6. Add the files in your new local repository. ...





6. Commit the files that you've staged in your local repository.







git add string.c  // adds files to the staging area.
                   // You can propose changes (add it to the Index) using 
git commit -m "Commit message"  // Now the file is committed to the HEAD, but not in your remote repository yet.


Your changes are now in the HEAD of your local working copy. To send those changes to your remote repository, execute 
git push origin master

Git Workflow

![One can think of git/GitHub version control process as a state machine.](
https://github.com/WhatMeWorry/SoupToNuts/blob/master/images/GitStateMachine.png)







