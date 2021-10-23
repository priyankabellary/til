# Basic Bash Commands
### To change directory
```
cd Desktop

bb@kaivalya:~/Documents/test$ cd 
pbb@kaivalya:~$ cd -
/home/pbb/Documents/test
pbb@kaivalya:~/Documents/test$ 
pbb@kaivalya:~/Documents/test$ cd ..
pbb@kaivalya:~/Documents$ 
```

### Present working directory
```
pbb@kaivalya:~/Documents$ pwd
/home/pbb/Documents
```

### Clear screen
```
clear
```

### To create a directory
```
mkdir <directory name>
```

### To create a file
```
touch <filename>
```

### List files
```
ls
ls -lrt (list, reverse, time)
ls -la (list, hidden)
find . (show tree)
```

### Remove file/directories
```
rm <filename>
rm -rf <directoryname> (recursive, forced) 
```

### How to make a file executable
```
pbb@kaivalya:~/Documents/test$ touch newscript.sh
pbb@kaivalya:~/Documents/test$ ls -lrt
total 0
-rw-rw-r-- 1 pbb pbb 0 Oct 23 14:10 newscript.sh
pbb@kaivalya:~/Documents/test$ chmod +x newscript.sh 
pbb@kaivalya:~/Documents/test$ ls -lrt
total 0
-rwxrwxr-x 1 pbb pbb 0 Oct 23 14:10 newscript.sh
```

### Open a file in VIM editor
```
vim <filename>
```

### Print content of a file
```
cat <filename>
```