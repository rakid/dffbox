# -*- mode: ruby -*-
# vi: set ft=ruby :
 
Vagrant.configure("2") do |config|
 
  config.vm.provider :hyperv

  config.vm.box = "rakid/dff"
  config.vm.hostname = "dff"
  config.vm.synced_folder "www", "/var/www", type: "smb"
 
end