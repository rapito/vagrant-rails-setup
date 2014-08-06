Vagrant Rails Setup
===================

Sets up a development-ready environment for a ***Ruby on Rails*** project 
on Vagrant box ```hashicorp/precise64```.

Pre-requisites:
---------
- Vagrant 1.6.2 or higher.

Features:
---------

- MongoDB
- Ruby
- Rails
- Git Configuration
- Color Scheme for bash

Installation:
---------

To use follow these steps:

- Copy all directories in this repository to the root folder of your rails project.
- Edit ```vagrant-setup.sh``` to replace ***[your-name]*** and ***[your-email]*** for github.
- ```vagrant up``` on project root.
- After the VM finishes booting, execute ```vagrant-setup.sh```

Done! The VM will start installing everything it needs and then you are ready to go.
Happy Coding!

Credits:
---------

- [Vagrant](http://www.vagrantup.com/)
