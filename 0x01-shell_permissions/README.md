#!/bin/bash
su betty changes the current user to betty
whoami prints the effective username of the current user
groups prints all the groups the current user is part of
sudo chown betty hello changes the owner of the file hello to the user betty
touch hello prints an empty file called hello
chmod u+x hello adds execute permission to the owner of the file hello
chmod u=x,g=x,o=r hello adds execute permission to the owner and the group owner, and read permission to  users, to the file hello
mkdir -m 751 my_dir creates a directory called my_dir with permissions 751 in the working directory
chgrp school hello changes the group owner to school for the file hello
sudo chown -R vincent:staff 0x01-shell_permissions changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
