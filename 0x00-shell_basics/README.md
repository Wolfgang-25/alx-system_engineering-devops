#!/bin/bash
pwd  prints the absolute path name of the current working directory
ls displays the contents list of your current directory
cd ~ changes from working directory to home directory
ls -l displays current directory contents in a long format
ls -la displays current directory contents, including hidden files (starting with .). Use the long format
ls -na displays current directory contents in Long format with user and group IDs displayed numerically and hidden files (starting with .)
mkdir /tmp/my_first_directory creates a directory named my_first_directory in the /tmp/ directory
mv /tmp/betty /tmp/my_first_directory moves betty from /tmp to /tmp/my_first_directory
rm /tmp/my_first_directory/betty deletes the file betty from /tmp/my_first_directory
rm -r /tmp/my_first_directory deletes my_first_directory from tmp
cd - changes the working directory to the previous one
ls -la . .. /boot lists the content of the working directory its parent directory and /boot directory all in long format showing hidden files
file prints the type of file iamafile is in the tmp directory
ln -s creates the symbolic link
cp -u --recursive --no-clobber --update *.html copies all html files in the working and parent directories 
