The su betty script switches the current user to 'betty'
The script whoami prints the username of the current user
 The sudo groups script prints all the groups the current user is part of
The script sudo chown betty hello changes the owner of file hello to the user betty
This script touch hello creates an empty file "hello"
This script chmod u+x hello adds execute permissions to the owner of the file hello
This script chmod 754 hello adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
This script chmod ugo+x hello adds execution permission to the owner, group owner and the other users
This script chmod 007 hello sets permission to file hello as follows: owner, no permission. group, no permission. others, all permission
This script chmod 754 adds full permission to owner, read and execute to group, and write and execute to others
This script chmod --reference=olleh hello copies the permission of olleh to the file hello
This script chmod -R ugo+X . Sets directories to be executable without modifying ordinary files in the current directory
This script mkdir -m 751 my_dir creates a directory called my_dir and gives it  a permission of 751 which means owner has full permission, groups are able to read and execute and others would be able to execute only
This script chgrp school hello changes the group of hello to school
