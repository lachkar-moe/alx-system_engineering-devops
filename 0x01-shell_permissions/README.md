Shell permissions

su = switch to specified user
whoami = print the current user
group = print all groups the current user is part of
chown = change the owner of a file or the group
touch = create an empty file
chmod u+x = give execution permission to the owner of the file\n
chmod ug+x, o+r = give the owner and the group owner permission to execute a file
chmod ugo+x = give everyone the permission to execute a file
chmod 007 = only others are granted all the permissions
chomd 753 = give all permission to the owner, r and x to the group and w x to others
chmod --reference = copy permission of another file
chmod -R +X = change permission to all subdirectories
mkdir -m = make new directory and assign its permission 
chgrp = change group owner of a file 
chown user:group * = change owner and group to all files and dirs inside 

