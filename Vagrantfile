Vagrant.configure("2") do |config|
    config.vm.box = "ubuntu/bionic64"
    
    config.vm.provider "virtualbox" do |v|
    v.memory = 1024
    end

    config.vm.define "teste" do |m|
    m.vm.network "private_network", ip: "192.168.100.100"
    end

    config.vm.define "dbteste" do |m|
    m.vm.network "private_network", ip: "192.168.100.110"
    end

end
