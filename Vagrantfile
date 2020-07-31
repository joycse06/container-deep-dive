Vagrant.configure("2") do |config|
  config.vm.box = "alpine/alpine64"

  config.vm.synced_folder "~/Code/container-deep-dive", "/home/vagrant/containers"

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "12000"
    vb.cpus = "6"
  end
end
