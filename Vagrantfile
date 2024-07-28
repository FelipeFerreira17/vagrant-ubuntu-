
Vagrant.configure("2") do |config|
 
config.vm.box = "ubuntu/focal64"
config.vm.provider "virtualbox" do |v|
	v.name = "VMdoProjeto"
	v.memory = 1024
	v.cpus = 1
end

config.vm.synced_folder "pastaprj1/", "/srv/site"
config.vm.network "public_network", bridge: " Realtek RTL8723B Wireless LAN 802.11n USB 2.0 Network Adapter"

  
end
