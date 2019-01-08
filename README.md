# vm-arch

This is a set of scripts designed to automate the creation of a minimal VM running Arch Linux, with timezone set to Madrid, and keyboard in Spanish.


## Installation
Boot the VM on archlinux iso and then run the command
```shell
wget https://goo.gl/8Ecbxe -O install.sh
bash install.sh [user] [password] [fast]
```
All arguments are optional and will be prompted for if not passed on invocation:
- `[user]` is your username
- `[password]` is what you want the root and user password to be
- `[fast]` is boolean 1 or 0 and controls using `rankmirrors` during set up which will be slow

The install.sh script will run and then reboot the computer once done.


It's a modified version  of https://github.com/abrochard/spartan-arch.
