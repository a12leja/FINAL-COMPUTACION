Vagrant.configure("2") do |config|
  config.vm.define :servidorUbuntu do |servidorUbuntu|
  #config.vm.provision :shell, path: "bootstrap.sh"
  servidorUbuntu.vm.box = "bento/ubuntu-20.04"
  servidorUbuntu.vm.network :private_network, ip: "192.168.100.3"
  servidorUbuntu.vm.hostname = "servidorUbuntu"
  servidorUbuntu.vm.provision "shell", path: "provision.sh"
  end
end