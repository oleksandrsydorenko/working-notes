# How to generate SSH key

1. Run in terminal `ssh-keygen -t rsa -C "<EMAIL>" -f "<USERNAME>"`
2. Copy generated files to `~/.ssh` folder\
`cp <USERNAME> ~/.ssh/`\
`cp <USERNAME>.pub ~/.ssh/`
3. Add key to auth agent `ssh-add -K ~/.ssh/<USERNAME>`