Vagrant.require_version ">= 1.7.0"

Vagrant.configure(2) do |config|

  config.vm.hostname = "TechTestVM"
  config.vm.box = "generic/centos8"

  config.vm.provider :virtualbox do |vb|
    vb.customize ["modifyvm", :id, "--memory", "4096", "--cpus", "2"]
  end
  
  config.vm.network :private_network, ip: "192.168.2.30"

  config.ssh.insert_key = false

  config.vm.provision "ansible" do |ansible|
    ansible.verbose = "v"
    ansible.playbook = "cluster_prep.yml"
  end
end