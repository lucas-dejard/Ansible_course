# Start virtualbox and configs
Vagrant.configure("2") do |config|
    config.vm.box = "ubuntu/trusty64"
    config.vm.provider "virtualbox" do |v|
        v.memory = 1024
    end

    # Start worpress machine
    config.vm.define "wordpress" do |m|
        m.vm.network "private_network", ip: "192.168.56.0"
    end

end