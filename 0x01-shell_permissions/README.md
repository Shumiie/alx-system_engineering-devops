SHELL PERMISSIONS

#[0. My name is Betty (0-iam_betty)]
Create a script that switched the current user to user betty.
Script: su betty

#[1. Who am I (1-who_am_i)]
Write a script that prints the effective username of the current user.
Script: whoami 

#[2. Groups (2-groups)]
Write a script that prints all the groups the current user is part of.
Script: groups

#[3. New owner (3-new_owner)]
Write a script that changes the owner of the file hello to the user betty. 
Script: chown betty hello

#[4. Empty! (4-empty)]
Write a script that creates an empty file called hello.
Script: touch hello

#[5. Execute (5-execute)]
Write a script that adds execute permission to the owner of the file hello.
Script: chmod u+x  hello 

#[6. Multiple permissions (6-multiple_permissions)]
Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
Script: chmod  ug+x,o+r hello

#[7. Everybody! (7-everybody)]
Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello. 
Script: chmod ugo+x hello

#[8. James Bond (8-James_Bond)]
Write a script that sets the permissions to the file hello as follows: 
Owner: no permissions at all
Group: no permissions at all
Other users: all the permissions 
Script: chmod 007 hello

#[John Doe (9-John_Doe)]
Write a script that sets the mode of the file hello to this: 
-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
Script: chmod  753  hello

#[10. Look in the mirror (10-mirror_permissions)]
Write a script that sets the mode of the file hello the same as olleh’s mode.
Script: chmod —reference=olleh hello

#[11. Directories (11-directories_permissions)]
Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
Script: chmod -R +X .

#[12. More directories (12-directory_permissions)]
Create a script that creates a directory called my_dir with permissions 751 in the working directory.
Script: mkdir -m 751 my_dir

#[13. Change group (13-change_group)]
Write a script that changes the group owner to school for the file hello. 
Script: chgrp school hello 

