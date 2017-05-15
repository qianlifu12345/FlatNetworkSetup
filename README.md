# FlatNetworkSetup
Host os:Ubuntu or MACOS
Virtualbox version:4.3
Need use VPN to inital the Vagrant images


### 1.1 Clone the project
```bash
git clone git@github.com:qianlifu12345/FlatNetworkSetup.git
```



### 2.1 Vagrant installation
To install the latest Vagrant

```bash
apt-get install vagrant
```


### 2.2 Create Virtual Mahine
#### 2.2.1 Create vagrantfile

Vagrantfile can be download from  [Vagrantfile](github.com) to your local folder.
#### 2.2.2 Bring up the virtual machines
Running the following command in the folder which contains the Vagrantfile.

```bash
vagrant up
```
#### 2.2.3 Login the virtual machine
To login the virtual machine:

```
vagrant ssh <virtual machine name>
```
The default user name is `vagrant`.
To get the super user privilige, use `sudo su -` command
