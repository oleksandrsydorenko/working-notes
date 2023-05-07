# Bash

## Disk

Show Disk Usage For Current Folder: `du -cha`\
Show Disk Usage For Current Folder Detailed: `du -chs`

## File System

Copy File: `cp <FILENAME_PATH> <DESTINATION_PATH>`\
Copy File Content: `pbcopy < <FILENAME_PATH>`\
Create File: `touch <FILENAME>`\
Show Current Shell: `echo $0`\
Show List Of Global Symbolic Links: `ls -al $(npm root -g)`\
Show List Of Local Symbolic Links: `ls -al ./node_modules`\
Show Working Directory: `pwd`\
Switch Shell Type: `chsh -s /bin/{{SHELL_TYPE}}`

## SSH

Add SSH key to auth agent: `ssh-add -K ~/.ssh/<USERNAME>`\
Generate SSH key: `ssh-keygen -t rsa -C "<EMAIL>" -f "<USERNAME>"`\
Add SSH key from auth agent: `ssh-add -d ~/.ssh/<USERNAME>`\

## User

Show Current User: `whoami`
