

## From Soup to Nuts ...

This is my first **markup** document. I am very _excited_ about this.

And I mean **_Really Excited!_**

I just created a new text file named firstMarkdown.md on my desktop. Then  
 
To view, open this file on a Windows computer in your Chrome Browser, Use the command is `ctrl + o` and then you can choose the file. On a Mac use `command + o`.

Also had to add a google extension called **Markdown Preview Plus** in order for Chrome to display markdown documents. Also had to go into the extension and click on the _Allow access to file URLs_


## GitHub setup
___

First create an user account on GitHub. My account's user is called *WhatMeWorry*

1. Create a new repository on GitHub. ...

(The following replaces a git init 
[gituser@CentOS project.git]$ git --bare init
Initialized empty Git repository in /home/gituser-m/project.git/)

    - In the upper-right corner of any page, click , and then click New repository.
    - Type a short, memorable name for your repository. ...
        ```SoupToNuts```
    - Optionally, add a description of your repository. ...
	    ```D 
		This repo documents the complete life cycle of a git/GitHub repository. 
	    Basically, a very detailed walk through.```
    - Choose between creating a public or private repository. ...
    - Select  [x] Initialize this repository with a README.
        ```This very text file firstMarkDown.md will become the README file.```
    - Click Create repository.
        ```D
        All repositories created on GitHub are considered *remote*.
        ```
To become really useful, a local copy of the remote repository needs to be created on your computer with a *clone* command. Cloning also keeps local and remote repositories synchronized.

___

2. Open TerminalTerminalGit Bash.

    - On windows open the Git Shell, Window's window is titled :/c/Users/kheaser/OneDrive for Business/GitHub
	- git shell's prompt is kheaser@IT-ASST-SB  ~/OneDrive for Business/GitHub $	

	On GitHub, navigate to the main page of the repository.

    At green Clone or download button, click "Clone or download."

    Clone URL buttonIn the Clone with HTTPs section, click  to copy the clone URL for the repository.

    Open Git Bash.

    Change the current working directory to the location where you want the cloned directory to be made.

    Type git clone, and then paste the URL you copied in Step 2.
	
	    ```D		
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
___	
	
		
3. Change the current working directory to your local project.
4. Initialize the local directory as a Git repository. ...
5. Add the files in your new local repository. ...
6. Commit the files that you've staged in your local repository.




git clone /path/to/repository    // create a working copy of a local repository by running the command

git add string.c  // adds files to the staging area.
                   // You can propose changes (add it to the Index) using 
git commit -m "Commit message"  // Now the file is committed to the HEAD, but not in your remote repository yet.


Your changes are now in the HEAD of your local working copy. To send those changes to your remote repository, execute 
git push origin master








