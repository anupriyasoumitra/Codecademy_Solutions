## 1. ls revisited
```script.js
$ ls
```

## 2. ls -a
```script.js
$ ls -a
. .. .preferences action drama comedy genres
```

## 3. ls -l
```script.js
$ ls -l
total 0
drwxr-xr-x 4 ccuser ccuser 172 Jul 8 2015 action
drwxr-xr-x 4 ccuser ccuser 77 Jul 8 2015 comedy
drwxr-xr-x 4 ccuser ccuser 38 Jul 8 2015 drama
-rw-r--r-- 1 ccuser 0 Jul 8 2015 genres.txt
```

## 4. ls -alt
```script.js
$ cd comedy
$ ls -alt
total 4
drwxr-xr-x 4 ccuser ccuser 77 Jul 8 2015 .
drwxr-xr-x 5 ccuser ccuser 85 Jul 8 2015 ..
-rw-r--r-- 1 ccuserccuser 0 Jul 8 2015 .gitignore
drwxr-xr-x 2 ccuser ccuser 28 Jul 8 2015 satire
drwxr-xr-x 2 ccuser ccuser 47 Jul 8 2015 slapstick
-rw-r--r-- 1 ccuser ccuser 14 Jul 8 2015 the-office.txt
$ cd ../drama/biopic/
$ls
cleopatra.txt frida.txt lincoln.txt notorious.txt ray.txt
$ cp frida.txt lincoln.txt
```

## 5. cp 1
```script.js
$ cd ..
$ cp biopic/cleopatra.txt historical/
$ cd historical/
$ ls
cleopatra.txt gladiator.txt selma.txt
$ cd drama/
$ cp biopic/ray.txt biopic/notorious.txt historical/
$ cd historical/
$ ls
cleopatra.txt gladiator.txt notorious.txt ray.txt selma.txt
```

## 6. cp 2
```script.js
$ cd ../../comedy
$ touch shrek.txt
cp: omitting directory 'satire'
cp: omitting directory 'slapstick'
$ cd satire/
$ ls
fight-club.txt shrek.txt the-office.txt
$ cd ../../action/
$ cp m*.txt scifi/
$ cd scifi/
$ ls
matrix-reloaded.txt matrix-revolutions.txt matrix.txt terminator.txt
```

## 7. wildcardsls
```script.js
$ cd ../
$ mv superman.txt superhero/
$ cd superhero
# ls
batman.txt superman.txt
$ cd ../action/
$ mv wonderwoman.txt batman.txt superhero/
$ cd superhero/
$ ls
superman.txt wonderwoman.txt batman.txt
$ mv batman.txt spiderman.txt
$ ls
spiderman.txt superman.txt wonderwoman.txt
```

## 8. mv
```script.js
$ cd ../../comedy/slapstick/
$ ls
waterboy.txt zoolander.txt
$ rm waterboy.txt
$ ls
zoolander.txt
$ cd ..
$ rm -r slapstick
$ ls
satire shrek.txt the-office.txt
```

## 9. rm
```script.js
MANIPULATION
The rm command deletes files and directories.
Here we remove the file waterboy.txt from the filesystem.

The -r is an option that modifies the behavior of the rm 
command. 
The -r stands for "recursive," and it's used to delete a 
directory and all of its child directories.

Be careful when you use rm! It deletes files and directories
permanently. There isn't an undelete command, so once you 
delete a file or directory with rm, it's gone.
```

## 10. Generalizations
```script.js
Congratulations! You learned how to use the command line to 
view and manipulate the filesystem. 

Options modify the behavior of commands:
ls -a lists all contents of a directory, including hidden files 
and directories.
ls -l lists all contents in long format.
ls -t orders files and directories by the time they were last
modified.
Multiple options can be used together, like ls -alt.

From the command line, you can also copy, move, and remove files 
and directories:
cp copies files
mv moves and renames files
rm removes files
rm -r removes directories
Wildcards are useful for selecting groups of files and directories
```




