Vagrant.configure(2) do |config|
  config.vm.box = "puppetlabs/centos-6.6-64-puppet"
  config.vm.network "forwarded_port", guest: 1521, host: 1521, auto_correct: true
  config.vm.network "forwarded_port", guest: 9990, host: 9990, auto_correct: true
  config.vm.network "forwarded_port", guest: 8080, host: 8080, auto_correct: true
end
