# [Ubuntu-Server-20.04 Vagrant Box](https://app.vagrantup.com/intuitum/boxes/ubuntu-server-20.04) 

This provides the configuration to build a [Vagrant](https://www.vagrantup.com) minimal box using [Packer](https://www.packer.io). 

## Usage Instructions

### Prerequisites

The build environment required is Mac OSX or GNU Linux.

To build the box file you will need the following installed:

- [VirtualBox](https://www.virtualbox.org) (6.1.2)
- [Vagrant](https://www.vagrantup.com) (2.2.18)
- [Packer](https://www.packer.io) (1.7.4)

### Build and Run Box

1. Clone this repository: 
```
$ git clone https://github.com/intuitum-io/packer-ubuntu-server.git
```

2. Go to the root directory. 
```
$ cd packer-ubuntu-server/
```
3. To build the `x86_64` box, run:
```
$ packer build ubuntu-server.json
```
4. To run the box, run: 
```
$ vagrant up 
```
5. To ssh into the box, run: 
```
$ vagrant ssh
```
