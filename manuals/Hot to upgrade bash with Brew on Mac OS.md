# How to upgrade bash with Brew on Mac OS

1. Confirm the active bash version: `bash --version`
2. Confirm the location of active bash: `which bash`
3. Confirm default shell for active user: `dscl . -read /Users/$USER UserShell`
4. Install bash with Brew: `brew install bash`
5. Confirm the location of Brew’s bash: `ls -la /usr/local/bin/bash`
6. Confirm the details of Brew's bash: `brew info bash`
7. Set the Brew's bash as default shell: `sudo dscl . -create /Users/$USER UserShell /usr/local/bin/bash`
8. Restart terminal
9. Confirm the location of active bash: `which bash`
10. Confirm the active bash version: `echo $BASH_VERSION`
11. Confirm the default shell for active user: `dscl . -read /Users/$USER UserShell`
12. Confirm the environmental variable: `echo $SHELL`