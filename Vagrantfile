# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.hostname = "phabricator.local"
  config.vm.network "private_network", ip: "192.168.100.21"

  config.vm.provider :virtualbox do |virtualbox|
      virtualbox.name = "phabricator"
      virtualbox.customize ["modifyvm", :id, "--memory", 512]
  end
  
  config.vm.provision :ansible do |ansible|
    ansible.playbook = "provision/phabricator.yml"
    ansible.host_key_checking = false
    ansible.groups = {
      "vm" => ["default"],
    }
  end
end