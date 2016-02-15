Vagrant.configure(2) do |config|
  config.vm.box = "puppetlabs/centos-6.6-64-puppet"
  config.vm.network "forwarded_port", guest: 1521, host: 1521, auto_correct: true
end
