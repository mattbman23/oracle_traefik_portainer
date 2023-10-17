Vagrant.configure("2") do |config|
    config.vm.box = "eurolinux-vagrant/oracle-linux-8"

    # provision controller node
    config.vm.define "controller" do |controller|
      controller.vm.hostname = "controller"
      controller.vm.network "private_network", ip: "192.168.56.10" 
      controller.vm.provider "virtualbox" do |vb|
        vb.memory = 2048
        vb.cpus = 2
      end
    end 
  end
    