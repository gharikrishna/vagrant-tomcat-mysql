vagrant-tomcat
==============

This demo code is tested with Vagrant 1.0.2 and VirtualBox 4.1.10.

This is a simple example of how to build a virtual test environment with Vagrant and Puppet.

The setup contains two virtual machines, one database server with MySQL and one application server with Tomcat 6.

Simply check it out, chdir into the directory and then run

> vagrant up

to start the two boxes.

You'll then have your application server at http://33.33.33.10:8080 and your database server listens on 33.33.33.11. Enjoy!

When you're done, don't forget to stop your virtual boxes with

> vagrant halt

or completely remove them with

> vagrant destroy
