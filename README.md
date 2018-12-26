# dev-machine

My current development machine. This is a Vagrantfile that has been customized to use Ubuntu 16.04 LTS.

1. Install Vagrant and VirtualBox on your host machine
1. Create a Development folder in your home directory
1. Clone this to your local machine, preferably in a Vagrant folder `git clone https://github.com/bsp3ars/dev-machine.git`
1. Go into the cloned folder `cd Vagrant\dev-machine`
1. Add the vbguest plugin `vagrant plugin install vagrant-vbguest`
1. Update and start the machine `vagrant up`
1. Connect to the machine `vagrant ssh`
1. When finished, you can exit the machine with `exit` or Ctrl + d
1. To shutdown the machine, you can do `vagrant halt`

Notes:

When you update the Vagrantfile, you need to run `vagrant reload` for the changes to be visible

To delete the machine, use `vagrant destroy` and then delete the dev-machine folder
