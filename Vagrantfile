# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "hardeep/saucy64"

  config.ssh.username = "ubuntu"
  config.ssh.forward_agent = true

  config.vm.network :private_network, ip: "192.168.50.5"

  config.vm.synced_folder ".", "/vagrant", :nfs => true
end
