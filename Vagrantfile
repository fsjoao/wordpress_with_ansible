Vagrant.configure("2") do |config|

    config.vm.box = "ubuntu/trusty64"
  
    #config.ssh.private_key_path = "chave privada"
    #config.ssh.host = "172.17.177.40"
    #config.ssh.port = 22
  
    config.vm.provider "virtualbox" do |v|
         v.memory = 1024
    end
  
    config.vm.define "wordpress" do |m|
         m.vm.network "private_network", ip: "172.17.177.40"
    end
  end
  