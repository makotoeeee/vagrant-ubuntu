# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu-16.04"
  config.vm.box_url = "https://atlas.hashicorp.com/ubuntu/boxes/xenial64/versions/20160521.0.0/providers/virtualbox.box"
  config.vm.network :public_network, bridge: 'en0: Wi-Fi (AirPort)'

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "1024"
  end
end
