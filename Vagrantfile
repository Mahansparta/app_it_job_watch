# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/bionic64"
  config.vm.synced_folder "app_it_job_watch", "/home/ubuntu/app"

  config.vm.provision "shell", path: "provisions.sh", privileged: false
end 
