# How to debug npm module

1. Create global symbolic link in a module’s root folder directory: `npm link`
2. Add symbolic link of a module to your project: `npm link <MODULE NAME>`
3. Require module from your project. Now any changes made in a module will be reflected in a project

To delete symbolic link run: `sudo npm rm --global <MODULE NAME>`
