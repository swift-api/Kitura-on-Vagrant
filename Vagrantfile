# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/wily64"
  config.vm.provision :shell, path: "InstallScript/InstallKitura.sh"
  config.vm.network :forwarded_port, guest: 8090, host: 8090
end