## Instructions to set up VM using Vagrant.

### Steps:
1. Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads) and [Vagrant](https://www.vagrantup.com/downloads.html).
2. Clone the repo from the following [URL](
   https://github.com/SoftwareEngineeringToolDemos/ICSE-2011-InconsistencyInspector.git)
3. Navigate to this directory where it is cloned from terminal. This is the project root.
4. Navigate to the build-vm directory and run the command 'vagrant up'.
5. This is what you will observer during installation.
    * Base image is downloaded.
    * Virtual machine is created.
    * Virtual machine is started in GUI mode.
    * Virtual machine is named as 'InconsistencyInspector'
    * Open JDK 7 is installed on the machine.
    * Mercurial is installed.
    * Project is cloned on the Virtual Machine.
    * Readme, Installation, Lincense and "How to use Inconsistency Inspecotor" files are added on the desktop.
    * Unused folders are removed.
    * Unused sidebar icons are removed.
    * VM is restarted.
    
### Login Credential:
    * Username: vagrant
    * Password: vagrant

### Tool in action:
To make the tool work, please go through the [Readme.txt](https://github.com/SoftwareEngineeringToolDemos/ICSE-2011-InconsistencyInspector/blob/master/build-vm/VM-Documents/readme.txt) file.
This is the link for [YouTube video](https://www.youtube.com/watch?v=ha_JOdqqzTE)

### References:
* Vagrant - Getting Started https://docs.vagrantup.com/v2/getting-started/up.html
* Open JDK installation guide - http://openjdk.java.net/install/
* http://superuser.com/questions/164553/automatically-answer-yes-when-using-apt-get-install
* Shell Provisioner: https://docs.vagrantup.com/v2/provisioning/shell.html
* Vagrant VirtualBox Image used : https://atlas.hashicorp.com/box-cutter/boxes/ubuntu1404-desktop
* Disable USB Controller: http://hameedullah.com/vagrant-101-basic-virtual-machine-customizations.html
* Enable Auto-login: https://wiki.ubuntu.com/LightDM
* Disable Lock Screen: http://askubuntu.com/questions/177348/how-do-i-disable-the-screensaver-lock
* Remove unused icons: http://askubuntu.com/questions/416303/remove-dead-link-in-unity-dock
