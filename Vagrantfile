# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  config.vm.box = "ubuntu/trusty64"

  config.vm.network :forwarded_port, guest: 9000, host: 9000
  config.vm.network "private_network", type: "dhcp"

  # config.vm.provider "virtualbox" do |vb|
  #
  #   # Customize the amount of memory on the VM:
  #   vb.memory = "1024"
  # end
  #
  # View the documentation for the provider you are using for more
  # information on available options.

  config.vm.provision :shell, :path => "bootstrap.sh"

end
