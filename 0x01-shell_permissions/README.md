#!/bin/bash
su betty changes the current user to betty
whoami prints the effective username of the current user
groups prints all the groups the current user is part of
sudo chown betty hello changes the owner of the file hello to the user betty
touch hello prints an empty file called hello
chmod u+x hello adds execute permission to the owner of the file hello
chmod u=x,g=x,o=r hello adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
chmod ugo+x hello adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 007 hello sets the permission to the file hello as follows:Owner: no permission at all Group: no permission at all Other users: all the permissions
chmod 753 hello
chmod --reference=olleh hello sets the mode of the file hello the same as olleh’s mode
chmod -R ugo+X . adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
