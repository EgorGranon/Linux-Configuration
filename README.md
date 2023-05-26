# Linux-Configuration
## Contents

In this tutorial we will be going through several of the following configuration options possible in linux using the terminal:

| Chapter | Description |
|-----:|-----------|
|     1| Switching to root account privileges and locking another user account|
|     2| Copy files to a different directory |
|     3| Move a directory to a different directory |
|     4| Remove a file from a directory |
|     5| Change the user owner of a file |
|     6| Change the group owner of a file |   

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
-Step 1:
--
Type <b> mv SOURCE DEST</b> as follows :
<br />
<br />
<img src="https://imgur.com/UxERopU.png" height="65%" width="65%" alt="File Explorer"/>
<br />
<br />
We can see by listing the contents of the cflynn directory that the project directory was successfully moved.
