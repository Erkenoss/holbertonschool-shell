Add 0-iam_betty with su betty. Switch user or super user betty

Add 1-who_am_i with whoami. Tell what user I actually am

Add 2-groups with groups. Tell what group i actually am

Add 3-new_owner with chown betty hello. Change user of hello for give it to betty

Add 4-empty with touch hello. Create an empty file call hello

Add 5-execute with chmod u+x hello. Give the autorization to execute file hello for the current user

Add 6-multiple_permissions with chmod 754 hello. Give all autorisation for the current user, not the xrite possibility for the group and just the possibility to read for the other.

Add 7-everybody with chmod +x hello. Give the execute possibility for current user, group and other

Add 8-James_Bond with chmod 007. Give all possibiity for other but nothing to user and group

Add 9-John_Doe with chmod 753. As 6- but only write and execute for the other

Add 10-mirror_permissions with --reference=olleh hello. Give the same permissions for hello than olleh

Add 11-directories_permissions with chmod -R ugo+X. Give for everyone to execute all the directory and the current directory but don't change the file. -R for recursively in the diffrent repertory target. -X for only directory.

Add 12-directory_permissions with mkdir -m=751 my_dir. Give to a specific directory the autorization 751.

Add 13-change_grou with chgrp school hello. Change the group owner of hello to school.

Add 14-change_owner_and_group with chown vincent:staff *. Change the owner and the group owner of every file and directiry in the current directory to vincent and staff

Add 15-symbolic_link with chown -h vincent:staff _hello. Change owner for a symbolic link and only a symbolic link with -h.

Add 16-if_only chown --from=guillaume vincent hello. If the owner is guilaume the owner is vincent.  
