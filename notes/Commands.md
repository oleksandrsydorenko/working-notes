# Commands

## Bash

Displays disk usage of files and folders : du -chs ./_
Displays disk usage of all files and folders : du -cha ./_

## Git

Commit Staged Files : git com <MESSAGE>
Stage & Commit Files : git coma <MESSAGE>

Create Branch Locally : git newbl <BRANCH>
Create Branch Remotely : git newbr <BRANCH>
Create Tag Locally : git tag <TAG>
Create Tag Remotely : git push origin <TAG>

List Branches : git br
Merge With Fast-Forward Strategy : git merff <BRANCH>

Remove Branch Locally : git rembl <BRANCH>
Remove Branch Remotely : git rembr <BRANCH>
Remove Tag Locally : git tag -d <TAG>
Remove Tag Remotely : git push --delete origin <TAG>

Reset All Untracked Changes : git wash
Search : git see <PHRASE>

Show Conflicts : git conf
Show History (Extended) : git hist
Show History (Simple) : git lol
Show Status : git st
Show Who Made Changes From-To Lines : git bla <FROM LINE>,<TO LINE> <FILE>

Switch Branch : git ch <BRANCH>

## NPM

Check Outdated Packages : npm outdated
List Global NPM Packages : npm list -g --depth 0
List Global Yarn Packages : yarn global list

## NVM

Install Node Version : nvm install <VERSION>
Uninstall Node Version : nvm uninstall <VERSION>
List Node Versions : nvm list
Set Node Version : nvm use <VERSION>

## Server

Start Node Server : npx http-server <PATH> <OPTIONS>
Start Python Server : python -m SimpleHTTPServer 3000

## Yarn

Check Outdated Packages : yarn outdated
