Vagrant.configure("2") do |config|
  config.vm.box = "generic/ubuntu2204"

  config.vm.network "forwarded_port", guest: 80, host: 8080

  config.vm.network "private_network", ip: "192.168.56.21"

  config.vm.define "alpcndlkvm" do |node|
    node.vm.hostname = "alpcndlkvm.local"
      node.vm.provision "ansible" do |ansible|
        ansible.playbook = "playbook_flask.yaml"
    end
  end

  config.vm.synced_folder ".", "/home/vagrant/project"

  config.vm.provider "virtualbox" do |vb|
   vb.memory = "1024"
   vb.cpus = "1"
  end

 config.vm.provision "shell", inline: <<-SHELL
   apt-get update
 SHELL

end
