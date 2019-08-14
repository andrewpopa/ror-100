Vagrant.configure("2") do |config|
  config.vm.box = "apopa/bionic64"
  config.vm.network "private_network", ip: "192.168.56.21"
  config.vm.network :forwarded_port, guest: 3000, host: 3000
  config.vm.hostname = "ror"
  config.vm.provision :shell, path: "scripts/ror_env.sh", privileged: false
end
