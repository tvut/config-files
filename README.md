# config-files
## Vagrantfile
Creates docker image for SSH into on Mac. Install git, gcc and gdb once set up. Once in directory with Vagrant file, call ```vagrant up --provider=docker``` to get it up the first time, then ```vagrant up``` everytime after. ```vagrant halt``` will shut the machine down.

You can do ```vagrant ssh-config``` in the directory of the Vagrantfile to get the ssh config which you can copy paste into the file ```~/.ssh/config``` so that VSCode can connect.
## .git-config
Goes in home directory. Use ```git config --global credential.helper store``` to enable credential store before you do any git work so the login is stored.
## .zshrc
Goes in home directory.
