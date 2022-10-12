# Basic Shell Scripting Project

This script will read a CSV file that contains 20 new Linux users.

It will create each user on the server and add to an existing group called 'Developers'.

It will also check for the existence of the user on the system, before attempting to create it. 

The user that is being created must have a default home folder.

Each user should have a .ssh folder within its HOME folder. If it does not exist, then it will be created.

For each user’s SSH configuration, We will create an authorized_keys file and add the below public key.
