#!/bin/bash
echo "Hello, World"prints “Hello, World”, followed by a new line to the standard output
echo echo "\"(Ôo)'" displays a confused smiley "(Ôo)'
cat /etc/passwd displays the content of the /etc/passwd file.
cat /etc/passwd /etc/hosts displays the content of /etc/passwd and /etc/hosts
tail /etc/passwd displays the last 10 lines of /etc/passwd
head /etc/passwd displays the first 10 lines of /etc/passwd
head -3 iacta | tail +3 displays the third line of the file iacta
echo 'Best School' > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*:\)creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School
ls -la > ls_cwd_content writes into the file ls_cwd_content the result of the command ls -la
tail -n 1 < iacta >> iacta duplicates the last line of the file iacta
find -name "*.js" -type f -delete deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders
find . -type d ! -path . -print | wc -l counts the number of directories and sub-directories in the current directory
ls -t | head displays the 10 newest files in the current directory
