# Configuration Management

The main purpose of this repository is create a virtual machine and configure it to run a simple web server.

- [Vagrant]()
- [Virtual machine]()
- [Ansible]()


## Vagrant

The first step is to install virtualbox and vagrant using ```apt-get install vagrant```, then we initialize a virtual machine and we start up our virtual machine.

[Here](https://atlas.hashicorp.com/boxes/search) and [here](http://www.vagrantbox.es/) you can find two lists with virtual machine images.

We execute the following lines from the command line:

```vagrant init precise32 http://files.vagrantup.com/precise32.box```

```vagrant up```

And now we connect to the machine with:

```vagran ssh```

If you use Windows you will need to use PuTTY to log into your machine.

If you want return to your machine you only need execute ```exit``` and if you want to destroy your virtual machine and remove the binary disk image you will run ```vagrant destroy``` . 


### Vagrantfile

#### References:

- Vagrant boxes: http://www.vagrantbox.es/
- https://drupalize.me/videos/installing-vagrant-and-virtualbox?p=1526


