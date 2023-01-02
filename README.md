
## Do not put your password in any linux command! otherwise it will get save in history and be visible to all




# linux_commands
- / ---> Root directory (as in linux , directories are arranged in a tree like structure)

## Absolute vs relative path

- an absolute path always starts with / (i.e root)
- cd [directory] ---> To move inside a subdirectory.

![ra2](https://user-images.githubusercontent.com/33677647/210182492-0e7a9b9d-dc2d-4839-9e24-0e0367979bfd.jpg)
![ra3](https://user-images.githubusercontent.com/33677647/210182493-ac61ba0b-690a-4c8b-abf3-a8844fedd5b5.png)
![ar](https://user-images.githubusercontent.com/33677647/210182583-f286d201-6d45-4a88-9e02-deb6d799a0b6.png)

- pwd --> to see your current directory. (**parent** directory/ print working directory)

- ls ---> to see all the folder of your current directory. (shows all the **children** of your current directory)
- ls -l ---> to see all the folder of your current directory. in a nice way
- ls -R ---> to just see the recursive sub-directories of sub-directories.
- ls -a ----> to see all the hidden directories.

- cd \	----> Move to the root folder of the file system.
- cd .. ----> Move one level up (one folder) in the file system.
- cd [directory] ---> To move inside a subdirectory.

- mkdir [directory name] ---> to create new folder/ directory .
- rmdir [directory name] ---> to delete a folder/ directory.

- touch FileName.txt ---> creates a text file of name 'FileName'.
- touch 1.txt ---> creates a text file of name '1'.
- touch .abc ---> to create a hidden file (put a dot before file name. a file which cannot be seen by the 'ls' command alone)


- mv 1.txt myFolder/ ---> it will move 1.txt inside a folder named myFolder.
- cp 2.txt myFolder/ ---> it will copy 2.txt inside a folder named myFolder.
- cp c/desktop/aaa.txt abc/xyz/ ---> Copies aaa.txt to new file path.

- sudo su ----> to convert from regular user to root user (it will as for admin password to conform)
- sudo apt-get update ---> This command updates the list for each outdated package that needs to get update on your system.
- sudo apt-get upgrade ---> This command actually downloads the new versions of outdated packages and install them on your system.
- sudo apt install [package name] ----> to install any package like snail, apache2 etc.
- sudo apt install vim ----> vim is a command line text editor, once you install vim, use can easily edit text editors in command line.

- vim harry.txt ---> to change the content of a text file, vim is a text editor, 'i' for insert, ':w' to exit without save, ':wq' to exit with save.
- history ---> to see the history of all commands run by me.

- echo Helow World ---> Hellow World.
- printf "Hellow World" ---> Hellow World.

- top ---> shows the running components which are consuming your most resources.
- ps ----> shows all running processes
- Kill [PID number] ---> to kill any process using its process id (PID), just type ps, see all running commands, copy the PID of desired process to be killed.

- ssh myUserName@server_ip_address ---> to connect to to server using linux (it will ask for password)
![ooo](https://user-images.githubusercontent.com/33677647/210198386-149bbf98-f5f2-4697-9362-56273878c7af.png)


## Regular User VS Root User VS Service User :

- A regular user has full control on his own dirctories ($ represents regular user)
- A Root/ admin/ Super user has access to the directory of all other peoples directories as well
- A shortcut to run command as a root user is to use 'Sudo' before any command.<br/>
E.g :<br/>
if you want to create a new file abc.txt in someone esle directory, just simply use 'sudo' <br/>
(sudo touch abc.txt)<br/>
- Service users a the user working on servers<br/>




