---
id: sqreebagz792q1a2zshgenm
title: Basics
desc: ''
updated: 1649911451746
created: 1649159735848
---
> a command is usually in the form of  
> `<command> [OPTION]... [ARGUMENTS] OR [FILE]...`

- **touch** : create a file.

- **mkdir** : create a directory/ folder.

- **rm** : removes any file.

- **rmdir** : removes an entire directory.
  >the directory needs to be empty to perform rmdir.
  > Else do `rm -rf`.

- **mv** : move or rename a file/ directory.

- **cat** : used to print out contents of a file (and combine files). Alternative, `bat`.

- **man** : used to view documentation of a program.    
  > **whatis** can be used to search for man pages related to a command or program.  
  > **apropos** can be used to search for all instances of command or program in the man page directory.
  >
  > `info` is also an alternative to man pages.

- **ls** : used to list the contents of a directory
  > `ls` can be used with `-a` option to list all files (hidden files also) & `-l` to get a detailed list.

- **sudo** : used to grant temporary root privlage to non-root users. See [[sudo|linux.commands.sudo]].

- **whereis** : looks throught the filesystem to find the programs with matching name.

- **locate** : same as `whereis` but for files.

- **pwd** : prints present working directiory.

- **cd** : change directory.
  >(**cd**) or (**cd ~**) : change dir to home folder.  
  >**cd ..** : change dir to the parent folder of current directory.  
  >**cd -** : change to the previous directory, you where last in.

- **tree** : displays the tree view of the file system.
  > `tree` can be used with `-d` option to just view directories in a filesystem and to suppress listing of files.
