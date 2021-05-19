# How to upgrade zsh with Brew on Mac OS

1. Confirm the active zsh version: `zsh --version`
2. Confirm the location of active zsh: `which zsh`
3. Confirm the default shell for active user: `dscl . -read /Users/$USER UserShell`
4. Install zsh with Brew: `brew install zsh`
5. Confirm the location of Brew’s zsh: `ls -la /usr/local/bin/zs*`
6. Confirm the details of Brew's zsh: `brew info zsh`
7. Set the Brew's zsh as default shell: `sudo dscl . -create /Users/$USER UserShell /usr/local/bin/zsh`
8. Restart terminal
9. Confirm the location of active zsh: `which zsh`
10. Confirm the active zsh version: `zsh --version`
11. Confirm the default shell for active user: `dscl . -read /Users/$USER UserShell`
12. Confirm the environmental variable: `echo $SHELL`