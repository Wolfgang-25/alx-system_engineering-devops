#!/bin/bash
alias ls="rm *" creates an alias Name: ls Value: rm *
echo "hello $USER" prints hello user, where user is the current Linux user
export PATH=$PATH:/action adds /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1)) creates a script that counts the number of directories in the PATH
