
Vagrant.configure("2") do |config|
  config.vm.provider "virtualbox" do |vb|
    vb.name = "Previc_lab01"
    vb.memory = 4096
    vb.cpus = 2
end


   config.vm.box = "ubuntu/bionic64"
   config.vm.network "forwarded_port", guest: 80, host: 8095
   #config.vm.provision "shell",  path: "script.sh"

  end
