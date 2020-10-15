# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|
 config.vm.define :ansible do |ansible_host|
    ansible_host.vm.box = "debian/buster64"
    ansible_host.vm.network :public_network, :public_network => "wlp61s0"
    ansible_host.ssh.forward_agent = true
    ansible_host.ssh.shell = "/bin/sh"
 end

 config.vm.define :cst do |cst_host|
    cst_host.vm.box = "debian/buster64"
    cst_host.vm.network :public_network, :public_network => "wlp61s0"
    cst_host.ssh.forward_agent = true
    cst_host.ssh.shell = "/bin/sh"
 end

end
