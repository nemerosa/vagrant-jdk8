Vagrant::Config.run do |config|
  config.vm.box = "hashicorp/precise64"
  
  config.vm.provision :puppet do |puppet|
    puppet.module_path = "modules"
    puppet.options = "--verbose --debug"
  end
end