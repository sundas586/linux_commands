## Do not put your password in any linux command! otherwise it will get save in history and be visible to all

![commands3](https://user-images.githubusercontent.com/33677647/221394543-aac8ecea-5570-4d40-9ff2-9f875b3dc52b.png)

##  LINUX vs Windows :

Directory     |   Folder<br/> 
Package       |   Software<br/> 
Administrator |   root<br/> 
File          |   File<br/>
/             |   \     
Root User     |   Administrater

![akakak](https://user-images.githubusercontent.com/33677647/221095474-d0564289-1b8d-4a13-9650-283df63da09c.png)

**HW** : RAM, Processors, Harddisk, etc.<br/>
**Kernel vs OS** :<br/> 
Kernel is a core element of the OS that converts the user query into the machine language. so that  hardware can understand the task.<br/>
(The windows ka OS GUI based ha, jb hm os say koi task perform krtay han to wo command line m ja k wesay hi execute hota ha jesay hum direct linux ki command laga kr execute krtay han, to ya to GUI use kr k indirect way m command chalo k ye task perform kro computer, ya dirct cmd/ power shell m ja kr command chala do k ye kam kro computer, baat ak hi hogi, bs direct cmd m type krnay s speed bahr jati han q k UI ki ak layer kam hogai. Ub the thing is k chahe dirct command chalao ya GUI s command chalo ye commands cmd/powershell say hotay huay phir kernal k pass jati han or kernal in ko machine language 010101010 m convert kr dyta ha ta k Hardware ko smhj a jaye k krna kiya ha.)<br/> 
**Shell** :<br/> 
A shell is between the kernel and the user. A shell is a CLI (command-line interpreter). Hum chahe GUI krtay han to wo bhi pehlay CLI m ja k  run hota ha, CLI kernal ko ja kr btata he k bhai oper s ye order aya ha, phir kernal os order ko machine language m change kr dyta ha ta k hardware ko bhi smhj a jaye k ye ye kam krna ha.<br/>
The MS-DOS Shell, csh, ksh, PowerShell, sh, and tcsh are a few examples of shells.

## Advantages of Linux over windows :<br/> 

**Speed** : Linux m say GUI ki layer hat jati ha, CLI(Shell) k zrye banda kernel s direct baat kr layta ha.<br/> 
**Open Source/ Free** : if you want to use windows in your personal PC then you can download crack, but if a company uses it, then they will have to pay alot of money to purchse windows for each laptop, on the other hand, linux is totally free, so thats why all comapies uses linux.<br/>
**Security** :  
- If a virus enters in any folder of windows OS, it slowly prevails in all files and folder and slows down the PC, on the other hand, first it is very difficult to attack a linux kernel, and even if virus somehow enters any folder, than it stays only in that folder and can not prevail in other files, therefore it is more secure.
- Windows m agr virus a jaye to bohat mehabgay antivirus purchase krnay partay han, warna to phir pura windows dubara install kro, aray agr hamara system do saal s server par up tha ub ak galat file os m dalnay ki waja s virus ghus gya os m to m server m windows dubara thori krungi, company ka server down kr thori skti hun, jb k linux k case m ap simply effected file to delete kr k dusri file dal do na antivirus khareednay ki zrurt na dubara kernal install krnay ki zrurt k server bhi ban krna paray phir<br/>
**Easy Updates** : all softwares can be updated by on similar command.<br/>
**Light weight** : Low RAM comsumtion, small Os file, requires less storage and RAM.- to q k linux apnay ap ko run krwanay k liyai kam jaga gherti ha RAM m, to baki apps ki ziada jaga mil jati ha to processes speed up hojatay han.<br/>
**Multi user, distributed system** : We have our server up and running with linux kernel installed, all employees can use its harddisk, CPU, and storage at same time from there pc, but in actual they will be using this servers resources, all we have to do is to make multiple user n ids for unlimited users.
**So mant distributions** : the distributions of Windows (i.e window1,windows2,...11) are all made my Microsoft, BUT! there are a vast amount of linux distributions like ubuntu, kali linux, Redhd, Debian, Fidora

# Linux file system hierarchy / EVERY THING IS LINUX IS A FILE!!!:

- wheather it is your IP address or harddisk, RAM, storage info, Every thing is in a file.
- even as simple as a "**ls command, is a file!**", stored in /bin directory 
- So the fun thing is that the command "ls" that is used to list all files is its self a file :D

![commands2](https://user-images.githubusercontent.com/33677647/221392614-d8044883-7fc4-4720-827d-e6746d09f593.png)

![akakak](https://user-images.githubusercontent.com/33677647/221095688-faf24fc9-b82f-4159-a787-7bfdfbfe5f29.png)

Like in windows, if we have not created any folder yet, by C\ folder is created by default in windows OS, similarly in linux kernel, the bydefault root folder is **/** , which is the main folder . Jesay C m sari configuration files befault mojud hoti han wesay hi linux m bhi config files **/** folder m mojud hoti han,
jb hm linux install krtay han to jisay config files n folders C drive m befualt paray hotay han, wesay hi linux k "/" directory m bhi ye folders paray hotay han.

![commands](https://user-images.githubusercontent.com/33677647/221376318-5c0d57d1-1eca-455b-bef5-faec9dc0a124.png)

### /root vs /home :
Agr hum nay koi or acount nahi bnaya to by-default hm root user m login kr jayengay jis ki file **/root** ha, lakin agr hum nay different accounts bnaye han to id-password k hisab say hi hr bnada apnay account m ja skta ha.
or jo root user nahi hoga phir wo id-pass dal kr direct apnay regular acount m jaye ga jis ki file **/home** hoti ha, to wo jo bhi kam kryga /home ki directory m hi kryga. like : /home/waniya/abc.txt

### /boot

contains all files needed to boot up the system.

### /etc :

info of all configuration of your machine : harddisk , ram , processrores, etc.

# /USR vs /opt :

when ever we install any desired package(software) it is by default installed in /USR, if we want to install it in /opt, we can but /opt is optional, and /USR is by default.

### /bin vs /sbin :

- bin stands for **Binary**, and inside it are **command binaries** (i.e command files, because each command like pwd, ls, touch, they all are stored 
in /bin or /sbin directory in form of a file)
The commands that can be used only by root user are stored in /sbin and the commands that can be used by other common users stored in /bin directory.



## Absolute vs relative path

- an absolute path always starts with / (i.e root)
- cd [directory] ---> To move inside a subdirectory.

![ra2](https://user-images.githubusercontent.com/33677647/210182492-0e7a9b9d-dc2d-4839-9e24-0e0367979bfd.jpg)
![ra3](https://user-images.githubusercontent.com/33677647/210182493-ac61ba0b-690a-4c8b-abf3-a8844fedd5b5.png)
![ar](https://user-images.githubusercontent.com/33677647/210182583-f286d201-6d45-4a88-9e02-deb6d799a0b6.png)

## Linux Commands

- pwd --> to see your current directory. (**parent** directory/ print working directory)

- ls ---> to see all the folder of your current directory. (shows all the **children** of your current directory)
- ls -l ---> to see all the folder of your current directory. in a nice way
- ls -R ---> to just see the recursive sub-directories of sub-directories.
- ls -a ----> to see all the hidden directories.

- cd \	----> Move to the root folder of the file system.
- cd .. ----> Move one level up (one folder) in the file system.
- cd [directory] ---> To move inside a subdirectory.
- cd ----> get back home (location from where you started)

- mkdir [directory name] ---> to create new folder/ directory .
- rmdir [directory name] ---> to delete a folder/ directory.
- rm myfile.txt ---> to remove a text file
- rm -r abcFolder/ ---> as if you want to remove abcFolder, it will not untill all its subdirectories are removed, so use -r(recursive) to remove subdirectories.
- 

- touch FileName.txt ---> creates a text file of name 'FileName'.
- touch 1.txt ---> creates a text file of name '1'.
- touch .abc ---> to create a hidden file (put a dot before file name. a file which cannot be seen by the 'ls' command alone)


- mv 1.txt myFolder/ ---> it will move 1.txt inside a folder named myFolder.
- cp 2.txt myFolder/ ---> it will copy 2.txt inside a folder named myFolder.
- cp c/desktop/aaa.txt abc/xyz/ ---> Copies aaa.txt to new file path.
- sudo cp ls new_ls             ---> copies the ls command file and put in a new file named new_ls
- sudo rm ls                    ---> deletes the ls command file from /bin directory
- new_ls                        ---> this will print the name of sub-directories of your current directory as this file is the copy of ls file
- sudo cp new_ls ls             ---> to recover the ls file, just make a copy of new_ls.

- sudo su ----> to convert from regular user to root user (it will as for admin password to conform)
- sudo apt-get update ---> This command updates the list for each outdated package that needs to get update on your system.
- sudo apt-get upgrade ---> This command actually downloads the new versions of outdated packages and install them on your system.
- sudo apt install [package name] ----> to install any package like snail, apache2 etc.
- sudo apt install vim ----> vim is a command line text editor, once you install vim, use can easily edit text editors in command line.
- sudo useradd ali ---> to add a new user ali
- passwd ---> to change your own password
- vim harry.txt ---> to change the content of a text file, vim is a text editor, 'i' for insert, ':w' to exit without save, ':wq' to exit with save.

- history ---> to see the history of all commands run by me.
- cat myTextFile.txt ---> to see the text content of a file
- shred myTextFile ---> if you dont want anyone else to see the text of this file, use shred command and the text will look like encripted to them

- echo Helow World ---> Hellow World.
- echo "This is a text I want to save in sunnybunny file" > sunnybunny.txt ----> save txt in a file using echo and '>'
- printf "Hellow World" ---> Hellow World.
- nano sunnybunny.txt ----> nano will open the file of given name so that you edit it, and save
- vim harry.txt ---> to change the content of a text file, vim is a text editor, 'i' for insert, ':w' to exit without save, ':wq' to write n quit.

- which abc.txt ---> the if you have twp files of same name = abc.txt, stored in /a directory and also stored in /b directory, then which command will tell you k ye konsi    directory wali file ha. (which abc.txt ---> /b/abc.txt)
 

- top ---> shows the running components which are consuming your most resources.
- ps ----> shows all running processes
- Kill [PID number] ---> to kill any process using its process id (PID), just type ps, see all running commands, copy the PID of desired process to be killed.

-wget www.githubuser/bible.txt --> Wget is a free command-line utility and network file downloader, this line will download bible from internet.

- ssh myUserName@server_ip_address ---> to connect to to server using linux (it will ask for password)
![ooo](https://user-images.githubusercontent.com/33677647/210198386-149bbf98-f5f2-4697-9362-56273878c7af.png)
- whoami ---> will show you the username

### create a link to a file :
ln -s mytextfile.txt iAmLink ---> (-s = soft) now "iAmLink" will act as a link for this particular text file. [ln -s fileName LinkName]

## Regular User VS Root User VS Service User :

- A regular user has full control on his own dirctories ($ represents regular user)
- A Root/ admin/ Super user has access to the directory of all other peoples directories as well
- A shortcut to run command as a root user is to use 'Sudo' before any command.<br/>
E.g :<br/>
if you want to create a new file abc.txt in someone esle directory, just simply use 'sudo' <br/>
(sudo touch abc.txt)<br/>
- Service users a the user working on servers<br/>

## Different ways to create file in Linux (please check it out) :

https://phoenixnap.com/kb/how-to-create-a-file-in-linux

- cat = cat command can only create a file and we can also put text in it, but when it come to edit the text again, cat is not helpful.
- touch is only used to create  a empty file, no text putting or editing.
-  THE EDITORS :
- the VI/ VIM/ NANO commands are called editors because if we want to edit a file, we can adit them using one of these commands,
- Vi is older, Vim is old, Nano is the latest and most user friendlyu command.
-  please checkout the link above .

![commands4](https://user-images.githubusercontent.com/33677647/221396348-5fcadf1f-64d5-40d0-b765-541cf9a5adbb.png)



**Kernel vs OS** :<br/> 
Kernel is a core element of the OS that converts the user query into the machine language. so that  hardware can understand the task.<br/>
(The windows ka OS GUI based ha, jb hm os say koi task perform krtay han to wo command line m ja k wesay hi execute hota ha jesay hum direct linux ki command laga kr execute krtay han, to ya to GUI use kr k indirect way m command chalo k ye task perform kro computer, ya dirct cmd/ power shell m ja kr command chala do k ye kam kro computer, baat ak hi hogi, bs direct cmd m type krnay s speed bahr jati han q k UI ki ak layer kam hogai. Ub the thing is k chahe dirct command chalao ya GUI s command chalo ye commands cmd/powershell say hotay huay phir kernal k pass jati han or kernal in ko machine language 010101010 m convert kr dyta ha ta k Hardware ko smhj a jaye k krna kiya ha.)<br/> 
**Shell** :<br/> 
A shell is between the kernel and the user. A shell is a CLI (command-line interpreter). Hum chahe GUI krtay han to wo bhi pehlay CLI m ja k  run hota ha, CLI kernal ko ja kr btata he k bhai oper s ye order aya ha, phir kernal os order ko machine language m change kr dyta ha ta k hardware ko bhi smhj a jaye k ye ye kam krna ha.<br/>
The MS-DOS Shell, csh, ksh, PowerShell, sh, and tcsh are a few examples of shells.

## Advantages of Linux over windows :<br/> 

**Speed** : Linux m say GUI ki layer hat jati ha, CLI(Shell) k zrye banda kernel s direct baat kr layta ha.<br/> 
**Open Source/ Free** : if you want to use windows in your personal PC then you can download crack, but if a company uses it, then they will have to pay alot of money to purchse windows for each laptop, on the other hand, linux is totally free, so thats why all comapies uses linux.<br/>
**Security** :  
- If a virus enters in any folder of windows OS, it slowly prevails in all files and folder and slows down the PC, on the other hand, first it is very difficult to attack a linux kernel, and even if virus somehow enters any folder, than it stays only in that folder and can not prevail in other files, therefore it is more secure.
- Windows m agr virus a jaye to bohat mehabgay antivirus purchase krnay partay han, warna to phir pura windows dubara install kro, aray agr hamara system do saal s server par up tha ub ak galat file os m dalnay ki waja s virus ghus gya os m to m server m windows dubara thori krungi, company ka server down kr thori skti hun, jb k linux k case m ap simply effected file to delete kr k dusri file dal do na antivirus khareednay ki zrurt na dubara kernal install krnay ki zrurt k server bhi ban krna paray phir<br/>
**Easy Updates** : all softwares can be updated by on similar command.<br/>
**Light weight** : Low RAM comsumtion, small Os file, requires less storage and RAM.- to q k linux apnay ap ko run krwanay k liyai kam jaga gherti ha RAM m, to baki apps ki ziada jaga mil jati ha to processes speed up hojatay han.<br/>
**Multi user, distributed system** : We have our server up and running with linux kernel installed, all employees can use its harddisk, CPU, and storage at same time from there pc, but in actual they will be using this servers resources, all we have to do is to make multiple user n ids for unlimited users.
**So mant distributions** : the distributions of Windows (i.e window1,windows2,...11) are all made my Microsoft, BUT! there are a vast amount of linux distributions like ubuntu, kali linux, Redhd, Debian, Fidora

# Linux file system hierarchy / EVERY THING IS LINUX IS A FILE!!!:

- wheather it is your IP address or harddisk, RAM, storage info, Every thing is in a file.
- even as simple as a "**ls command, is a file!**", stored in /bin directory 
- So the fun thing is that the command "ls" that is used to list all files is its self a file :D

![commands2](https://user-images.githubusercontent.com/33677647/221392614-d8044883-7fc4-4720-827d-e6746d09f593.png)

![akakak](https://user-images.githubusercontent.com/33677647/221095688-faf24fc9-b82f-4159-a787-7bfdfbfe5f29.png)

Like in windows, if we have not created any folder yet, by C\ folder is created by default in windows OS, similarly in linux kernel, the bydefault root folder is **/** , which is the main folder . Jesay C m sari configuration files befault mojud hoti han wesay hi linux m bhi config files **/** folder m mojud hoti han,
jb hm linux install krtay han to jisay config files n folders C drive m befualt paray hotay han, wesay hi linux k "/" directory m bhi ye folders paray hotay han.

![commands](https://user-images.githubusercontent.com/33677647/221376318-5c0d57d1-1eca-455b-bef5-faec9dc0a124.png)

### /root vs /home :
Agr hum nay koi or acount nahi bnaya to by-default hm root user m login kr jayengay jis ki file **/root** ha, lakin agr hum nay different accounts bnaye han to id-password k hisab say hi hr bnada apnay account m ja skta ha.
or jo root user nahi hoga phir wo id-pass dal kr direct apnay regular acount m jaye ga jis ki file **/home** hoti ha, to wo jo bhi kam kryga /home ki directory m hi kryga. like : /home/waniya/abc.txt

### /boot

contains all files needed to boot up the system.

### /etc :

info of all configuration of your machine : harddisk , ram , processrores, etc.

# /USR vs /opt :

when ever we install any desired package(software) it is by default installed in /USR, if we want to install it in /opt, we can but /opt is optional, and /USR is by default.

### /bin vs /sbin :

- bin stands for **Binary**, and inside it are **command binaries** (i.e command files, because each command like pwd, ls, touch, they all are stored 
in /bin or /sbin directory in form of a file)
The commands that can be used only by root user are stored in /sbin and the commands that can be used by other common users stored in /bin directory.



## Absolute vs relative path

- an absolute path always starts with / (i.e root)
- cd [directory] ---> To move inside a subdirectory.

![ra2](https://user-images.githubusercontent.com/33677647/210182492-0e7a9b9d-dc2d-4839-9e24-0e0367979bfd.jpg)
![ra3](https://user-images.githubusercontent.com/33677647/210182493-ac61ba0b-690a-4c8b-abf3-a8844fedd5b5.png)
![ar](https://user-images.githubusercontent.com/33677647/210182583-f286d201-6d45-4a88-9e02-deb6d799a0b6.png)

## Linux Commands

- pwd --> to see your current directory. (**parent** directory/ print working directory)

- ls ---> to see all the folder of your current directory. (shows all the **children** of your current directory)
- ls -l ---> to see all the folder of your current directory. in a nice way
- ls -R ---> to just see the recursive sub-directories of sub-directories.
- ls -a ----> to see all the hidden directories.

- cd \	----> Move to the root folder of the file system.
- cd .. ----> Move one level up (one folder) in the file system.
- cd [directory] ---> To move inside a subdirectory.
- cd ----> get back home (location from where you started)

- mkdir [directory name] ---> to create new folder/ directory .
- rmdir [directory name] ---> to delete a folder/ directory.
- rm myfile.txt ---> to remove a text file
- rm -r abcFolder/ ---> as if you want to remove abcFolder, it will not untill all its subdirectories are removed, so use -r(recursive) to remove subdirectories.
- 

- touch FileName.txt ---> creates a text file of name 'FileName'.
- touch 1.txt ---> creates a text file of name '1'.
- touch .abc ---> to create a hidden file (put a dot before file name. a file which cannot be seen by the 'ls' command alone)


- mv 1.txt myFolder/ ---> it will move 1.txt inside a folder named myFolder.
- cp 2.txt myFolder/ ---> it will copy 2.txt inside a folder named myFolder.
- cp c/desktop/aaa.txt abc/xyz/ ---> Copies aaa.txt to new file path.
- sudo cp ls new_ls             ---> copies the ls command file and put in a new file named new_ls
- sudo rm ls                    ---> deletes the ls command file from /bin directory
- new_ls                        ---> this will print the name of sub-directories of your current directory as this file is the copy of ls file
- sudo cp new_ls ls             ---> to recover the ls file, just make a copy of new_ls.

- sudo su ----> to convert from regular user to root user (it will as for admin password to conform)
- sudo apt-get update ---> This command updates the list for each outdated package that needs to get update on your system.
- sudo apt-get upgrade ---> This command actually downloads the new versions of outdated packages and install them on your system.
- sudo apt install [package name] ----> to install any package like snail, apache2 etc.
- sudo apt install vim ----> vim is a command line text editor, once you install vim, use can easily edit text editors in command line.
- sudo useradd ali ---> to add a new user ali
- passwd ---> to change your own password
- vim harry.txt ---> to change the content of a text file, vim is a text editor, 'i' for insert, ':w' to exit without save, ':wq' to exit with save.

- history ---> to see the history of all commands run by me.
- cat myTextFile.txt ---> to see the text content of a file
- shred myTextFile ---> if you dont want anyone else to see the text of this file, use shred command and the text will look like encripted to them

- echo Helow World ---> Hellow World.
- echo "This is a text I want to save in sunnybunny file" > sunnybunny.txt ----> save txt in a file using echo and '>'
- printf "Hellow World" ---> Hellow World.
- nano sunnybunny.txt ----> nano will open the file of given name so that you edit it, and save
- vim harry.txt ---> to change the content of a text file, vim is a text editor, 'i' for insert, ':w' to exit without save, ':wq' to write n quit.

- which abc.txt ---> the if you have twp files of same name = abc.txt, stored in /a directory and also stored in /b directory, then which command will tell you k ye konsi    directory wali file ha. (which abc.txt ---> /b/abc.txt)
 

- top ---> shows the running components which are consuming your most resources.
- ps ----> shows all running processes
- Kill [PID number] ---> to kill any process using its process id (PID), just type ps, see all running commands, copy the PID of desired process to be killed.

-wget www.githubuser/bible.txt --> Wget is a free command-line utility and network file downloader, this line will download bible from internet.

- ssh myUserName@server_ip_address ---> to connect to to server using linux (it will ask for password)
![ooo](https://user-images.githubusercontent.com/33677647/210198386-149bbf98-f5f2-4697-9362-56273878c7af.png)
- whoami ---> will show you the username

### create a link to a file :
ln -s mytextfile.txt iAmLink ---> (-s = soft) now "iAmLink" will act as a link for this particular text file. [ln -s fileName LinkName]

## Regular User VS Root User VS Service User :

- A regular user has full control on his own dirctories ($ represents regular user)
- A Root/ admin/ Super user has access to the directory of all other peoples directories as well
- A shortcut to run command as a root user is to use 'Sudo' before any command.<br/>
E.g :<br/>
if you want to create a new file abc.txt in someone esle directory, just simply use 'sudo' <br/>
(sudo touch abc.txt)<br/>
- Service users a the user working on servers<br/>

## Different ways to create file in Linux (please check it out) :

https://phoenixnap.com/kb/how-to-create-a-file-in-linux

- cat = cat command can only create a file and we can also put text in it, but when it come to edit the text again, cat is not helpful. 
- touch is only used to create  a empty file, no text putting or editing.
-  THE EDITORS :
- the VI/ VIM/ NANO commands are called editors because if we want to edit a file, we can adit them using one of these commands,
- Vi is older, Vim is old, Nano is the latest and most user friendlyu command.
-  please checkout the link above .

![commands4](https://user-images.githubusercontent.com/33677647/221396348-5fcadf1f-64d5-40d0-b765-541cf9a5adbb.png)

- Cat is useful to combine multiple text file together as on
- touch is useful as it keeps the timestamp of file creation and updation.
- VI is less user friendly but more powerful than Nano

- press "i" to insert any text in text editor
- after writing your desired text, after done, press "esc" button, so compiler will know that you are done.
- then type ":wq" to save the text and get out of file.<br/>
![commands](https://user-images.githubusercontent.com/33677647/221407314-0e8d9d8d-bba5-4d05-a206-1b2011fa5d71.png)
