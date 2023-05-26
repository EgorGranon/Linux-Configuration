# Linux-Configuration
## Contents

In this tutorial we will be going through several of the following configuration options possible in linux using the terminal:

| Chapter | Description |
|-----:|-----------|
|     1| Switching to root account privileges and locking another user account|
|     2| Copy files to a different directory |
|     3| Move a directory to a different directory |
|     4| Remove a file from a directory |
|     5| Change the user owner and group owner of a file |
|     6| Change permissions of a file |

## Chapter 1: Switching to root account privileges and locking another user account
-Step 1:
---
Open the terminal from your Linux desktop and type in **su - root** 
<br />
<br />
If you have configured your root account to recquire identification to log in, type in your root user password. (!warning as you type in your password nothing will appear on screen. Continue typing your password and click enter.
<br />
<br />
If you have identified yourself successfully the following screen should appear:
<br />
<br />
<img src="https://imgur.com/mWgA9zS.png" height="65%" width="65%" alt="File Explorer"/>
<br />
<br />
-Step 2:
---
Type in <b>passwd [user name] -l</b> to lock the account as follows:
<br />
<br />
<img src="https://imgur.com/pgMAw6k.png" height="65%" width="65%" alt="File Explorer"/>
<br />
<br />
## Chapter 2: Copy files to a different directory
-Step 1:
---
Type in <b>cp SOURCE DEST</b> adn then check if the files have succesfully been copied using <b>ls</b> as follows :
<br />
<br />
<img src="https://imgur.com/5Gu0vQu.png" height="65%" width="65%" alt="File Explorer"/>
<br />
<br />
## Chapter 3: Move directory to a different directory
Type <b> mv SOURCE DEST</b> as follows :
<br />
<br />
<img src="https://imgur.com/UxERopU.png" height="65%" width="65%" alt="File Explorer"/>
<br />
<br />
We can see by listing the contents of the cflynn directory that the project directory was successfully moved.
## Chapter 4: Remove a file from a directory
-Step 1:
---
Type <b>rm [Option] file...</b>
-Step 2:
---
When prompted to <b>remove regular file</b> type <b>y</b>
<br />
<br />
Output should be as follows:
<br />
<br />
<img src="https://imgur.com/iqhPJCK.png" height="65%" width="65%" alt="File Explorer"/>
<br />
<br />
As we can see by listing the contents of the <b>rcronn</b> directory the <b>personal_appointments</b> has been removed.
## Chapter 5: Change the user owner of a file
To change the user owner of a file type in : chown USER FILE
<br />
<br />
<img src="https://imgur.com/v7wtrbE.png" height="65%" width="65%" alt="File Explorer"/>
<br />
<br />
We can see when listing the files that initially the user owner of the <b>Welcome</b> file is <b>rcronn</b> but after using <b>chown</b> the user has switched to <b>cflynn</b>
To change the group owner of a file type in : chgrp GROUP FILE
<br />
<br />
<img src="https://imgur.com/YvA9ie1.png" height="65%" width="65%" alt="File Explorer"/>
<br />
<br />
## Chapter 6: Change permissions of a file
To change permissions of a file type <b>chmod [0-7][0-7][0-7] FILENAME</b>
as follows :
<br />
<br />
<img src="https://imgur.com/52badW4.png" height="65%" width="65%" alt="File Explorer"/>
<br />
<br />
As we can see above, each number 0-7 represents a 3 bit number. Where 0 represents 000 and 7 represents 111. The first bit represents r(read), second bit w(write) and third bit x(execute).If there is a 1 in place we turn the permission <b>on</b> if there is a 0 we turn the premission <b>off</b>. The first number represents the User, Second the Group and third Everone else.
