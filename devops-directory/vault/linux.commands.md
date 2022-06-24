---
id: uef9n2fojyopibvstxarv03
title: Commands
desc: ''
updated: 1649681201284
created: 1649135234875
---

### Navigating directory history

**pushd & popd** :  
- `pushd .` adds directories to a stack which can be itterated through by using `pushd +/-<num>`.
- to remove a directory from the stack use `popd`.
- use the `dirs` commands to print the directory stack.

**cdh** for fish shell : it allows you to list recently visited directories and quickly navigating through by their numeral enteries.

</br>

### Managing files

**find** : it lists all files in the current dirrectory as well as all its subdirectories.  
  - commonly used options are:  
    `-name` : use wildcards to search for a file.  
    `-type` : `d` for directory, `f` for file & `l` for symbolic link.
    > find /usr -name gcc-* -type f


**tac** : prints out a file backwards, starting with the last line.

**less** : used to view large files, provides scroll-back capabilities.

**ln -s** : used to create symlink or symbolic link of a file.

**head** : used to show the first few lines of a file.

**tail** : used to show the last few lines of a file.