vagrant-jdk8
============

Sources for creating the Vagrant Cloud [`nemerosa/jdk8`](https://vagrantcloud.com/nemerosa/boxes/jdk8) image.

JDK8 image for Vagrant.

To build the image, just run:

	vagrant up
	vagrant package --base <vm-name>

where `<vm-name>` is the name of the VM which has been created.

The list of VM can be accessed using:

	VBoxManage list vms
