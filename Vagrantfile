
Vagrant.configure("2") do |config|

  config.vm.box = "centos/7"

   config.vm.box_check_update = false



   config.vm.network "public_network", bringe: "wlp3s0", ip: "192.168.0.200"


   config.vm.provider "virtualbox" do |vb|
     vb.memory = "512"
   end


end
