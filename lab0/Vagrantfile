# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "bento/centos-7.2"
  config.vm.hostname = "cscd427"

  config.vm.provision "shell" do |s|
    s.path = "lab0/bootstrap.sh"
    s.name = "bootstrap"
  end

end
