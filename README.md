# Beginning Ruby Nanodegree Program VM

## Summary
This repository contains the files to set up the Virtual Machine
for the Beginning Ruby Nanodegree Program.

## Set up

1. Install [Vagrant](https://www.vagrantup.com/downloads.html)
2. Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
2. Install [Git](https://git-scm.com/downloads) and when you get to "Adjusting your PATH environment" select "Use Git and optional Unix tools from the Windows Command Prompt"
3. Copy the `vagrant` folder onto your computer (wherever you plan on keeping your Ruby projects)
4. Open up the command line, and navigate to the `vagrant` folder using `cd`
5. Run the command `vagrant up`

## Vagrant Usage

* `vagrant up`: starts up the VM
* `vagrant ssh`: starts the VM command line prompt
* `exit`: exits the VM command line prompt
* `vagrant halt`: shuts down the VM

## Shared folder

Once you start up the VM, you will be in the VM's home folder. There will
be one directory in the home folder: `rubynd`

The `rubynd` folder is a shared folder that exists in the VM, as well as in the `vagrant` folder on your computer. Any folders and files you add to `rubynd` can be accessed in the VM and on your computer.

Access the shared folder from within your VM command line terminal with:

```
cd rubynd
```
