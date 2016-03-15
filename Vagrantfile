# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "debian/jessie64"
  config.vm.provision :shell, path: "script.sh"
  config.vm.network "forwarded_port", guest: 80, host: 1120
  config.vm.network "public_network"
end
