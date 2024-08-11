Vagrant.configure("2") do |config|

    # Configuración para la primera máquina virtual
    config.vm.define "vm1" do |vm1|
      vm1.vm.box = "ubuntu/bionic64"
      vm1.vm.hostname = "vm1"
      vm1.vm.network "private_network", ip: "192.168.33.10"
      vm1.vm.provider "virtualbox" do |vb|
        vb.memory = "256"
        vb.cpus = 1
      end
    end
  
    # Configuración para la segunda máquina virtual
    config.vm.define "vm2" do |vm2|
      vm2.vm.box = "ubuntu/bionic64"
      vm2.vm.hostname = "vm2"
      vm2.vm.network "private_network", ip: "192.168.33.11"
      vm2.vm.provider "virtualbox" do |vb|
        vb.memory = "256"
        vb.cpus = 1
      end
    end
  
    # Configuración para la tercera máquina virtual
    config.vm.define "vm3" do |vm3|
      vm3.vm.box = "ubuntu/bionic64"
      vm3.vm.hostname = "vm3"
      vm3.vm.network "private_network", ip: "192.168.33.12"
      vm3.vm.provider "virtualbox" do |vb|
        vb.memory = "256"
        vb.cpus = 1
      end
    end
  
  end