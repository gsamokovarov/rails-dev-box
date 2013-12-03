Vagrant.configure('2') do |config|
  config.vm.box      = 'precise64'
  config.vm.hostname = 'rails-dev-box'

  config.vm.provision :puppet do |puppet|
    puppet.manifests_path = 'puppet/manifests'
    puppet.module_path    = 'puppet/modules'
  end
end
