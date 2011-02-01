Vagrant::Config.run do |config|

  config.vm.box = "lenny"

  config.vm.customize do |vm|
    vm.memory_size = 512
  end

  config.vm.forward_port "http", 80, 8080

end


