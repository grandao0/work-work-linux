work-work-linux
==============

I stand ready

#### Linux Commands:

`chmod o+w <dirPath>` -- changes the permission mode of the `other` a write permission

`chmod u-rwx <dirPath>` -- removes all of the permissions of the `users` on the directory

`chown` -- changes ownership

`clear` -- clears the terminal

`alias <aliasName>=<aliasCommand>` -- creates a long command abbreviated by the alias name

`cd <where>` -- navigate to a directory

`pwd` -- show in which directory you are

`ls` -- shows what is inside a directory

`mkdir` -- creates a directory

`rmdir` -- removes an empty directory

`touch <fileName>` -- creates a file

`rm <fileName>` -- removes a file

`cp <fleName> <where>` -- copy a file to a directory


`ifconfig` -- configure network interface parameters


`whoami` -- prints the current user

`users` -- list all users

`useradd <userName>` -- add a new user

`userdel <userName>` -- deletes a user

`usermod -aG <groupName> <userName>` -- add a user in a group

`id <userName>` -- shows information on user

`passwd <userName>` -- creates/changes the user password


`groups` -- list all groups

`groupadd <groupName>` -- add a new group

`groupdel <groupName>` -- deletes a group


`sudo` -- allows to run command as another user

`sudo -u <userName> <command>` -- runs the command as the chosen user

`su -` -- switch user

`yum repolist all` -- list all yum repositories

`yum info <software>` -- prints information on softwares

`yum install -y <software` -- installs the software as non-interactive as possible answering yes to all with `-y`

`yum update` -- updates all softwares installed

`yum update <software>` -- updates the passed software

`yum remove <software>` -- removes the passed software

`ls -l /etc/yum.repos.d` -- list all the repositories files
