# mbed GCC Toolchain - Vagrant

## Introduction



src folder contrains the code to be compiled.


## Requirements
* Vagrant 
* Virtualbox

## Install
After the installation has been done the a SSH port will be opened on the local host with the following details.
* SSH 127.0.0.1:2222
* Username : vagrant
* Password : vagrant

Shared folder:
On the Linux box fodler /vagrant is the same as the host folder where the vagrant folder is located.

## Usage
* Export a project from the Online mBed IDE(GCC toolchain)
* Extract the contents into the `src` folder 
* SSH to the Vagrant box (SSH details above)(I use Putty for windows and SSH for Linux)
* `cd /vagrant/src`
* `make`
* The `src` folder should now contain the binary files(bin,hex,elf) if the make command was succesfull.
