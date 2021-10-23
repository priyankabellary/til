# Basic Bash Commands
### 1.To change directory
cd Desktop

bb@kaivalya:~/Documents/test$ cd 
pbb@kaivalya:~$ cd -
/home/pbb/Documents/test
pbb@kaivalya:~/Documents/test$ 
pbb@kaivalya:~/Documents/test$ cd ..
pbb@kaivalya:~/Documents$ 

### 2.Present working directory
pbb@kaivalya:~/Documents$ pwd
/home/pbb/Documents

### 3.Clear screen
clear

### 4.To create a directory
mkdir <directory name>

### 5.To create a file
touch <filename>

### 6.List files
ls
ls -lrt (list, reverse, time)
ls -la (list, hidden)
find . (show tree)

### 7.Remove file/directories
rm <filename>
rm -rf <directoryname> (recursive, forced) 

### 8.How to make a file executable
pbb@kaivalya:~/Documents/test$ touch newscript.sh
pbb@kaivalya:~/Documents/test$ ls -lrt
total 0
-rw-rw-r-- 1 pbb pbb 0 Oct 23 14:10 newscript.sh
pbb@kaivalya:~/Documents/test$ chmod +x newscript.sh 
pbb@kaivalya:~/Documents/test$ ls -lrt
total 0
-rwxrwxr-x 1 pbb pbb 0 Oct 23 14:10 newscript.sh

### 9.Open a file in VIM editor
vim <filename>

### 10. Print content of a file
cat <filename>

### 11. Home directory as tidle
$ cat /home/pbb/.ssh/id_ed25519
$ cat ~/.ssh/id_ed25519
