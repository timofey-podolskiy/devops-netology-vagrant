Vagrant.configure("2") do |config|
    config.vm.box = "bento/ubuntu-20.04"
    config.vm.network "forwarded_port", guest: 9100, host: 9100, id: 'node_exporter'
    config.vm.network "forwarded_port", guest: 19999, host: 19999, id: 'netstat'
end