Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.network "forwarded_port", guest: 3000, host: 4444
  config.vm.synced_folder "sample_app/", "/home/vagrant/workspace/sample_app/"
end
