# Terminal_Code
Unknown
1.    ls : list directory contents(The ls command will show you the list of files in your current directory.)# ls
2.    cd : Change Directory(The cd command will allow you to change directories.)# cd
3.    pwd : print the current/working directory(The pwd command will allow you to know in which directory you are located)# pwd
4.    mkdir : make/create directory.( The mkdir command will allow you to create directories. )# mkdir 
5.    rmdir : remove the directory(The rmdir command will delete an empty directory.)# rmdir
6.    rm : remove/delete file.(This command to remove or delete a file in your directory.)# rm
7.    mv : rename or move a file/directory(The mv command will move a file to a different location or will rename a file.)# mv
8.    man : Manual pages for shell commands.(The man command is used to show you the manual of other commands.)# man rm
9.    cp : Copy Files(The cp command will make a copy of a file for you.)# cp r_test.txt r1_test.txt
10.  shutdown : Shutdown the computer from terminal( This command shutdown the computer )# shutdown ­hor# init 0
11.adduser : Addition of new user ( This command creating the new user in /home directory)# adduser ravi
12.passwd : Change password for user( This command change the password of specific user)# passwd ravi
13.tar :  Creates and extracts files from a tape or disk archive.(This command stores and extracts files from a tape or disk)# tar cvzf ravi.tar.gz *
14.tar :  Creates and extracts files from a tape or disk archive.(This command stores and extracts files from a tape or disk)# tar xvzf ravi.tar.gz 
15.find :  find searches the file located at /(This command find searches the directory tree rooted at each given file)# find / ­name ravi.txt ­print
16.grep :  print lines matching a pattern(This command searches the named input files for lines containing  a  match to the given pattern.)# grep ravi losarwar *
17# chown   (change file owner and group (This command  changes the user and/or group ownership of each given file.)
18# chgrp     (change group ownership (This command  change the  group of each file to group)
19# chmod    (change file mode bits (This command changes the file mode bits of each given file according to mode)
20# ifconfig  (This command  is  used to configure the kernel­resident network interfaces)# ifconfig


mv: Short for move, this command can be used to move your files from one folder to another. 
rm: Short for remove, this command is used to remove any files or folders.
cd: Short for change, you can use this command to change your current directory. 
cp: Short for copy, this command can be used to copy files or folders in a directory. 
chown: This command is used to change ownership of a file. 
chmod: This command is used to change permissions on a file. 
ls: Short for list, this command can be used to view all of the files and folders in your current working directory. 
pwd: Short for print working directory, this command can be used to display the directory in which you are currently working. 

sudo: Also referred to as superuser do, a sudo command allows you to run other commands with administrative privileges. 
This command is especially useful for modifying files in a directory that a user wouldn't necessarily have access to. 

cd: Short for change directory, this command can be used to change the directory in which you are currently working. 
There are a variety of cd commands that can be used to take you to specific files or folders. 

cd / : An alternate to a basic cd command, the cd / command can be used to take you to the root directory. 

cd .. : This command can be used to take you up one directory level. 

cd - : This command can be used to navigate to a previous directory.



Top 17 commands for Ubuntu Beginners
Basics GNU/Linux Commands
#1. ls : list directory contents

ls
If you want to see hidden files/directories (beginning with dot.), the use -a flag.

ls -a
Check the manual for more detail (man ls).

 

#2. cd : Change Directory

cd ../
cd /home/Desktop
Remember,

. represents the current directory

.. represents the parent directory

~ represents the home directory (of the user)

 

#3. pwd : print the current/working directory

pwd
/home/Desktop/scripts
 

#4. mkdir : make/create directory.

mkdir funny_stuffs
 

#5. rm : remove/delete file/directory

rm useless.sh
NOTE : it removes directories only if its empty, unless you specify -f flag for force deletion. But you must be careful with the arguments such as -r, -f. (-rf is very dangerous).

 

#6. sudo : superuser do, to gain root privilege

e.g

sudo apt-get install gnome-shell
Then enter your user account password, and you would be able to do administrative tasks like root. So if youre getting any permission error using a command, then adding sudo as a prefix, might help.

 

#7. mv : rename or move a file/directory

mv file1 ~/Downloads/Archive/
the above command will move the file from the current directory to target directory.

mv logo_2.jpg new_logo.jpg
it will rename the file to new_logo.jpg.

 

#8. cat : View File contents

cat install.log
 
