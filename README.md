# ubuntu_vagrant_with_user
Standard Vagrant Ubuntu setup with an ansible provisioner to create a user with the same name as the user on the host.

This is intended to be run on Mac. It may need some tweaking in the user role to run on other operating systems.

Requirements
* VirtualBox `brew cask install virtualbox`
* Ansible `brew install ansible`
* Vagrant `brew cask install vagrant`

Usage:
```
  vagrant up
  ssh 127.0.0.1 -p 2222
```
