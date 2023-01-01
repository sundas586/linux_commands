
## Do not put your password in any linux command! otherwise it will get save in history and be visible to all




# linux_commands
- / ---> Root directory (as in linux , directories are arranged in a tree like structure)

## Absolute vs relative path

- an absolute path always starts with / (i.e root)

![ra2](https://user-images.githubusercontent.com/33677647/210182492-0e7a9b9d-dc2d-4839-9e24-0e0367979bfd.jpg)
![ra3](https://user-images.githubusercontent.com/33677647/210182493-ac61ba0b-690a-4c8b-abf3-a8844fedd5b5.png)
![ar](https://user-images.githubusercontent.com/33677647/210182583-f286d201-6d45-4a88-9e02-deb6d799a0b6.png)

- pwd --> to see your current directory. (**parent** directory/ print working directory)
- ls ---> to see all the folder of your current directory. (shows all the **children** of your current directory)
- ls -R ---> to just see the recursive sub-directories of sub-directories.
- touch .abc ---> to create a hidden file (put a dot before file name. a file which cannot be seen by the 'ls' command alone)
- ls -a ----> to see all the hidden directories.
- cd [directory] ---> To move inside a subdirectory.
- mkdir [directory name] ---> to create new folder/ directory .
- touch FileName.txt ---> creates a text file of name 'FileName'.
- touch 1.txt ---> creates a text file of name '1'.
- mv 1.txt myFolder/ ---> it will move 1.txt inside a folder named myFolder.
- cp 2.txt myFolder/ ---> it will copy 2.txt inside a folder named myFolder.
- cp c/desktop/aaa.txt abc/xyz/ ---> Copies aaa.txt to new file path.
- sudo apt-get update ---> This command updates the list for each outdated package that needs to get update on your system.
- sudo apt-get upgrade ---> This command actually downloads the new versions of outdated packages and install them on your system.
- history ---> to see the history of all commands run by me.
- echo Helow World ---> Hellow World
- printf "Hellow World" ---> Hellow World
- 
- 

## Regular User VS Root User VS Service User :

- A regular user has full control on his own dirctories ($ represents regular user)
- A Root/ admin/ Super user has access to the directory of all other peoples directories as well
- A shortcut to run command as a root user is to use 'Sudo' before any command.<br/>
E.g :<br/>
if you want to create a new file abc.txt in someone esle directory, just simply use 'sudo' <br/>
(sudo touch abc.txt)<br/>
- Service users a the user working on servers<br/>




