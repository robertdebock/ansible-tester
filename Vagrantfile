Vagrant.configure("2") do |config|
  config.vm.define "centos-7" do |config|
    config.vm.box = "centos/7"
    config.vm.synced_folder '.', '/vagrant', disabled: true
    config.vm.provider :libvirt do |domain|
      domain.memory = 1024
      domain.cpus = 1
    end
  end
  # config.vm.define "centos-8" do |config|
  #   config.vm.box = "centos/8"
  #   config.vm.synced_folder '.', '/vagrant', disabled: true
  #   config.vm.provider :libvirt do |domain|
  #     domain.memory = 1024
  #     domain.cpus = 1
  #   end
  # end
  # config.vm.define "debian-stretch" do |config|
  #   config.vm.box = "debian/stretch64"
  #   config.vm.synced_folder '.', '/vagrant', disabled: true
  #   config.vm.provider :libvirt do |domain|
  #     domain.memory = 1024
  #     domain.cpus = 1
  #   end
  # end
  # config.vm.define "debian-buster" do |config|
  #   config.vm.box = "debian/buster64"
  #   config.vm.synced_folder '.', '/vagrant', disabled: true
  #   config.vm.provider :libvirt do |domain|
  #     domain.memory = 1024
  #     domain.cpus = 1
  #   end
  # end
  # config.vm.define "fedora-32" do |config|
  #  config.vm.box = "fedora/32-cloud-base"
  #  config.vm.synced_folder '.', '/vagrant', disabled: true
  #  config.vm.provider :libvirt do |domain|
  #      domain.memory = 1024
  #      domain.cpus = 1
  #  end
  # end
  # config.vm.define "fedora-33" do |config|
  #   config.vm.box = "fedora/33-cloud-base"
  #   config.vm.synced_folder '.', '/vagrant', disabled: true
  #   config.vm.provider :libvirt do |domain|
  #     domain.memory = 1024
  #     domain.cpus = 1
  #   end
  #   config.vm.provider :libvirt do |libvirt|
  #     libvirt.qemu_use_session = false
  #     libvirt.storage :file, :size => '64G'
  #   end
  # end
  # config.vm.define "ubuntu-xenial" do |config|
  #   config.vm.box = "generic/ubuntu1604"
  #   config.vm.synced_folder '.', '/vagrant', disabled: true
  #   config.vm.provider :libvirt do |domain|
  #     domain.memory = 1024
  #     domain.cpus = 1
  #   end
  # end
  # config.vm.define "ubuntu-bionic" do |config|
  #   config.vm.box = "generic/ubuntu1804"
  #   config.vm.synced_folder '.', '/vagrant', disabled: true
  #   config.vm.provider :libvirt do |domain|
  #     domain.memory = 1024
  #     domain.cpus = 1
  #   end
  # end
  # config.vm.define "ubuntu-focal" do |config|
  # config.vm.box = "generic/ubuntu2004"
  # config.vm.synced_folder '.', '/vagrant', disabled: true
  # config.vm.provider :libvirt do |domain|
  #   domain.memory = 1024
  #   domain.cpus = 1
  # end
end
