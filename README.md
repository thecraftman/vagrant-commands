# vagrant-commands

## What is vagrant
 
 Vagrant is a tool for working with virtual environments. Vagrant provides a simple and easy to use command-line client for managing environments. 

Download vagrant [here](https://www.vagrantup.com/downloads.html)

### Below is a list of some Vagrants Commands that vagrant provides to make managing your virtual machines much simpler. 

**- Vagrant Status**

This command shows the current status of the vi
al machine. It should currently read `default running (virtualbox)` along with some other information.

**- Vagrant Suspend**

This command suspends the virtual machine. Most of the work done is saved and the machine is put into a `sleep mode of sorts`. The machine state is saved and it’s very quick to stop and start the work done.

This command is applicable if you don't want to leave the machine running during short breaks.
   

**- Vagrant Up**

This command gets the virtual machine up and running again. 

**- Vagrant ssh**

This Command will actually connect to and log into the Virtual machine. Once this is implemented a few lines of text will be displayed showing various performance statistics of the virtual machine along with a new command line prompt that reads **vagrant@vagrant-ubuntu-trusty-64:~$**

**- Vagrant halt** 

This command halts the virtual machi. All the work done on it is saved and the machine is turned off. This acts more as `"turning the power off"`. It’s much slower to stop and start your virtual machine using this command, but it does free up all of your RAM once the machine has been stopped.


