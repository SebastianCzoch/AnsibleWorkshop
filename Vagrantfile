# -*- mode: ruby -*-
# vi: set ft=ruby :
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "puphpet/debian75-x64"
  config.vm.network "private_network", ip: "192.168.33.20"
  config.vm.synced_folder ".", "/var/www" , 
  owner: "www-data", group: "www-data"
end
