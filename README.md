# One-line-cli
Useful things that I forget....


Go to your A directory and run

`find . -mindepth 2 -type f -print -exec mv {} . \;`

which means "find all files in this directory and its sub-directories and execute mv with target directory . for each file found to move them to current directory.
