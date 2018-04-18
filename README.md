# One-line-cli
Useful things that I forget....


Go to your A directory and run

`find . -mindepth 2 -type f -print -exec mv {} . \;`

which means "find all files in this directory and its sub-directories and execute mv with target directory . for each file found to move them to current directory. *** this will overwrite files with the same name. if you have files with the same file name in different subfolders, you will overwrite all of these with the last find. Better to use mv with --backup=numbered: `find . -mindepth 2 -type f -print -exec mv --backup=numbered {} . \;`
