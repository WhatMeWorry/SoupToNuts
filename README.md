

## Git and GitHub Walk-Thru, from Soup to Nuts ...

### Overview
This is an introduction to Git version control system. It teachs by doing: a step by step walkthru of all the commands listed in the required order. It is believed that theory is better understood after the user first knows the lay of the land. For Git to become really powerful/useful, it needs to paired with a remote repository.  

### Requirements
1. A computer running Windows 7/8/10 computer, Mac OS, or Linux with git downloaded [https://git-scm.com/downloads](https://git-scm.com/downloads) and installed.

    Note: there are git GUI clients but for learning purposes, we'll just stick to the shell. GUIs will just be an unnecessary distraction.

2. A GitHub user account [https://github.com/](https://github.com/) (This is remote/web based account) 

    Note: GitHub is independent of Git. There are other remote GitHub competitors like Bitbucket, GitLab, and SourceForge, but we will use GitHub here.

``` 
To view, open this file on a Windows computer in your Chrome Browser, Use the command is `ctrl + o` and then you can choose the file. On a Mac use `command + o`.

Also had to add a google extension called **Markdown Preview Plus** in order for Chrome to display markdown documents. Also had to go into the extension and click on the _Allow access to file URLs_
```


## GitHub Setup

1. Create a [GitHub user account](https://github.com/join)

2. After logging in to GitHub account, [create a remote repository](https://github.com/new)

    [detail instructions](./documentation/GitHubRepoSetup.txt)

To become really useful, a local copy of the remote repository needs to be created on your computer with a *clone* command. Cloning also keeps local and remote repositories synchronized.

3. After remote repo has been created, [clone](./documentation/CloningRemoteRepo.txt) it to your local machine. 

	
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







