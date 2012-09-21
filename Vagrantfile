Vagrant::Config.run do |config|

  # it is required to have 'base' base box for this vm to work
  config.vm.box = "lucid32"

  # forward port
  config.vm.forward_port 80, 8080

  # provision with a shell script
  config.vm.provision :shell, :path => "provision.sh"

  # change name of the vm
  config.vm.customize ["modifyvm", :id, "--name", "Startup VM"]

  # move .vagrant file (system specific) to ~/
  # config.vagrant.dotfile_name = "~/.vagrant-overallmurals"

end
