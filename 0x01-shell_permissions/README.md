#!/bin/bash
0-iam_betty switches the current user to the user betty
1-who_am_i prints the effective username of the current user
2-groups prints all the groups the current user is part of
3-new_owner chaneges the owner of the file hello to the user betty
4-empty creates an empty file called hello
5-execute adds execute permissions to the owner of the file hello
6-multiple_permissions adds execute permissions to the owner and the group owner and read permission to oher users to thefile hello
7-everybody adds execute permission to the owner, the group owner and other users
8-James_Bond sets: owner, no permissiona at sll, group no permissiona at all, other users, all the permissions
9-John_Doe sets mode of the file to -rwxr-x-wx
10-mirror_permissions sets mode of hello same as olleh
11-directories_permissions adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
12-directory_permissions creates directory dir_holberton with permission 751 in the working directory
13-change_group changes the group owner to holberton for the file hello
100-change_owner_and_the_group change owner to betty and the group owner to holberton for all files and directoies in the working directory
101-symbolic_link_permissions changes the owner and gruop owner of _hello to betty and holberton respectively
102-if_only changes the owner of the file hello to betty only if its owned by the user guillaume
103-Star-Wars plays StartWars IV episode in terminal