## Instructions to set up VM using Vagrant.

### Steps:
* Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads) and [Vagrant](https://www.vagrantup.com/downloads.html).
* Create a new directory and place this [VagrantFile](https://github.com/SoftwareEngineeringToolDemos/ICSE-2011-InconsistencyInspector/blob/master/build-vm/Vagrantfile) in it.
* Navigate to this directory from terminal.
* Run the command "vagrant up". This will create a new ubuntu 14.04 LTS virtual machine and install openjdk-1.7 in it.
* There are two ways to login into this virtual machine.
  * Use the gui provided by the Virtualbox.
  * Use ssh client(like putty or vagrant ssh) to start a new ssh session.
* Credentials for login.
  * Username: vagrant
  * Password: vagrant

### References:
* Vagrant - Getting Started https://docs.vagrantup.com/v2/getting-started/up.html
* Open JDK installation guide - http://openjdk.java.net/install/
* http://superuser.com/questions/164553/automatically-answer-yes-when-using-apt-get-install
* Shell Provisioner: https://docs.vagrantup.com/v2/provisioning/shell.html
* Vagrant VirtualBox Image used : https://atlas.hashicorp.com/box-cutter/boxes/ubuntu1404-desktop
