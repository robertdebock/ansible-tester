Vagrant.configure("2") do |config|
#  config.vm.define "alpine" do |alpine|
#    alpine.vm.box = "generic/alpine37"
#    alpine.vm.synced_folder '.', '/vagrant', disabled: true
#  end
  config.vm.define "fedora28-1" do |fedora28|
    fedora28.vm.box = "fedora/28-cloud-base"
    fedora28.vm.synced_folder '.', '/vagrant', disabled: true
    fedora28.vm.provider :libvirt do |domain|
        domain.memory = 4096
        domain.cpus = 2
    end
  end
#  config.vm.define "fedora28-2" do |fedora28|
#    fedora28.vm.box = "fedora/28-cloud-base"
#    fedora28.vm.synced_folder '.', '/vagrant', disabled: true
#    fedora28.vm.provider :libvirt do |domain|
#        domain.memory = 2048
#        domain.cpus = 2
#    end
#  end
#  config.vm.define "fedora28-3" do |fedora28|
#    fedora28.vm.box = "fedora/28-cloud-base"
#    fedora28.vm.synced_folder '.', '/vagrant', disabled: true
#    fedora28.vm.provider :libvirt do |domain|
#        domain.memory = 4096
#    end
#  end
#  config.vm.define "centos6" do |centos6|
#    centos6.vm.box = "centos/6"
#    centos6.vm.synced_folder '.', '/vagrant', disabled: true
#  end
#  config.vm.define "centos7" do |centos7|
#    centos7.vm.box = "centos/7"
#    centos7.vm.synced_folder '.', '/vagrant', disabled: true
#    centos7.vm.provider :libvirt do |domain|
#      domain.memory = 4096
#      domain.cpus = 2
#    end
#  end
#  config.vm.define "opensuse" do |opensuse|
#    opensuse.vm.box = "opensuse/openSUSE-42.3-x86_64"
#    opensuse.vm.synced_folder '.', '/vagrant', disabled: true
#  end
  config.vm.define "ubuntu" do |ubuntu|
    ubuntu.vm.box = "generic/ubuntu1804"
    ubuntu.vm.synced_folder '.', '/vagrant', disabled: true
    ubuntu.vm.provider :libvirt do |domain|
      domain.memory = 4096
      domain.cpus = 2
    end
  end
#  config.vm.define "archlinux" do |archlinux|
#   archlinux.vm.box = "archlinux/archlinux"
#    archlinux.vm.synced_folder '.', '/vagrant', disabled: true
#  end
#  config.vm.define "freebsd" do |freebsd|
#    config.vm.box = "generic/freebsd11"
#  end
end
