## FILES function
1) we know that a file is between a / and a .blah
2) a file can also have no extension. 🤮 meaning #1 is false.
3) there is a bash command to figure out file. 🎉
4) there is a bash command to figure out directory. 🎉

## FOLDERS function
5) if directory is found keep going ... keeping path.
6) if no file or directory was found ... it must be a command that uses a directory! 🎉 this is arg1

## RESOLVED
1) argument has been found go on to next argument using files function.

## For FOLDERS

## For Files
Folders can be figured out by regex searching / and  /
Files can be figured from folders bu regex searching '.' from the substring.

