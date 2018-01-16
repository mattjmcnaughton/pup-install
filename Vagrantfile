# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "geerlingguy/ubuntu1604"

  config.vm.network :private_network, ip: '192.16.2.5'
  config.vm.hostname = 'pup-install-test'
  config.ssh.insert_key = false

  config.vm.provision 'ansible' do |ansible|
    ansible.playbook = 'test.yml'
  end
end
