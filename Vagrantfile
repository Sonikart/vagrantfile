Vagrant.configure("2") do |config|
  config.vm.box = "debian/stretch64"
  config.vm.network "private_network", ip: "192.168.50.50"
  config.ssh.forward_agent = true
  config.vm.provider "virtualbox" do |v|
  	v.memory = 2048
  	v.cpus 	= 2
  end
end
