#Vagrantfile

Vagrantfile needed to build your vitulabox from [Bento](https://github.com/chef/bento)

#HowTo

#Install
Install Vagrant

Install VirtualBox

Install Omnibus Plugin

$vagrant plugin install vagrant-omnibus

#Add & Edit
Use the appropriate file from repository.

Bento-Win: Run from Windows
Bento-Linux: Run from Linux

Make sure you install the Chef keys and edit the file.

#Run
$vagrant up
$vagrant ssh


#Destroy

$vagrant destroy

$knife node delete server -y
$knife client delete server -y
