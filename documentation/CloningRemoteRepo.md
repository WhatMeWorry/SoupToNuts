 

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