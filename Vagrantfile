Vagrant.configure(2) do |config|
  config.vm.provider "virtualbox" do |v|
    v.memory = 512 
  end
  config.vm.box = "ubuntu-14.04"
  config.vm.box_url = "https://cloud-images.ubuntu.com/vagrant/trusty/current/trusty-server-cloudimg-amd64-vagrant-disk1.box"
  config.vm.define "th" do |v|
    v.vm.network "private_network", ip: "192.168.33.99"
  end
end
