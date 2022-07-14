# Linux Cheatsheet

> `pwd` 
Present working directory.
----
> `ls` 
List of contents in directory.
`ls -al`
`ll`
`ll -ah`
-----
> `tree`
List of all directories and files present in it.
---
> `cd`
To change directory.
`cd ..`
Go back to previous directory.
---
>`mkdir`
To create directory.
`mkdir new{1..10} -v`
To create multiple directories "-v" flag for success message.
---
>`rmdir`
To remove empty directory.
---
>`rm`
To remove directory and its content.
`-r -rh` flags 
---
>`*`
Flag use to select multiple files.
---
>`touch`
To create new file with name.
---
> `cat`
To read contents of files.
`cat > content file.name`
Overrides the file content.
`cat >> content file.name`
Append new line and adds new content.
---
>`cp file_name /location`
copy file with name and location.
`mv file_name /location1 /location2`
To move file from one location to another.
`mv file newfile`
To rename the file.
---
>`locate`
To search files `locate helloworld`.
---text 
>`echo`
>Shell print command.
---
>`gedit`
>In build text editor.
---
>`sudo`
>Super user command.
---
>`df -h` / `du`
>Disk usage 
---
>`uname -a`
>Kernal details
---
>`chmod`
>To change file permission (+rwx / -rwx)
>r - read
>w - write
>x - executable
---
>`lshw`
>Hardware information.
---
>`neofetch`
>CPU overview
---
>`ping`
>To check internet connection `ping www.google.com` 
---
>`apt list -installed`
>To list all installed apps in system
---
