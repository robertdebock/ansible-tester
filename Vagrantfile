Vagrant.configure("2") do |config|
#  config.vm.define "alpine" do |alpine|
#    alpine.vm.box = "generic/alpine38"
#    alpine.vm.synced_folder '.', '/vagrant', disabled: true
#    alpine.vm.provider :libvirt do |domain|
#        domain.memory = 4096
#        domain.cpus = 2
#    end
#  end
#  config.vm.define "fedora" do |fedora|
#    fedora.vm.box = "fedora/rawhide"
#    fedora.vm.synced_folder '.', '/vagrant', disabled: true
#    fedora.vm.provider :libvirt do |domain|
#        domain.memory = 4096
#        domain.cpus = 2
#    end
#  end
#  config.vm.define "fedora28" do |fedora28|
#    fedora28.vm.box = "fedora/28-cloud-base"
#    fedora28.vm.synced_folder '.', '/vagrant', disabled: true
#  end
#  config.vm.define "fedora29" do |fedora28|
#    fedora28.vm.box = "fedora/29-cloud-base"
#    fedora28.vm.synced_folder '.', '/vagrant', disabled: true
#    fedora28.vm.provider :libvirt do |domain|
#        domain.memory = 4096
#        domain.cpus = 4
#        domain.storage :file, :size => '20G'
#    end
#  end
#  config.vm.define "fedora29" do |config|
#    config.vm.box = "fedora/29-cloud-base"
#    config.vm.synced_folder '.', '/vagrant', disabled: true
#    config.vm.provider :libvirt do |libvirt|
#      libvirt.storage :file, :size => '20G'
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
  config.vm.define "centos7-1" do |centos7|
    centos7.vm.box = "centos/7"
    centos7.vm.synced_folder '.', '/vagrant', disabled: true
    centos7.vm.provider :libvirt do |domain|
      domain.memory = 4096
      domain.cpus = 2
      domain.storage :file, :size => '20G'
    end
  end
#  config.vm.define "centos7-2" do |centos7|
#    centos7.vm.box = "centos/7"
#    centos7.vm.synced_folder '.', '/vagrant', disabled: true
#    centos7.vm.provider :libvirt do |domain|
#      domain.memory = 4096
#      domain.cpus = 2
#      domain.storage :file, :size => '20G'
#    end
#  end
#  config.vm.define "opensuse" do |opensuse|
#    opensuse.vm.box = "opensuse/openSUSE-42.3-x86_64"
#    opensuse.vm.synced_folder '.', '/vagrant', disabled: true
#  end
#  config.vm.define "ubuntu16" do |ubuntu|
#    ubuntu.vm.box = "generic/ubuntu1604"
#    ubuntu.vm.synced_folder '.', '/vagrant', disabled: true
#    ubuntu.vm.provider :libvirt do |domain|
#      domain.memory = 4096
#      domain.cpus = 2
#    end
#  end
#  config.vm.define "ubuntu17" do |ubuntu|
#    ubuntu.vm.box = "generic/ubuntu1704"
#    ubuntu.vm.synced_folder '.', '/vagrant', disabled: true
#    ubuntu.vm.provider :libvirt do |domain|
#      domain.memory = 4096
#      domain.cpus = 2
#    end
#  end
#  config.vm.define "ubuntu18" do |ubuntu|
#    ubuntu.vm.box = "generic/ubuntu1810"
#    ubuntu.vm.synced_folder '.', '/vagrant', disabled: true
#    ubuntu.vm.provider :libvirt do |domain|
#      domain.memory = 4096
#      domain.cpus = 2
#      domain.storage :file, :size => '20G'
#    end
#  end
#  config.vm.define "debian9" do |debian|
#    debian.vm.box = "debian/stretch64"
#    debian.vm.synced_folder '.', '/vagrant', disabled: true
#    debian.vm.provider :libvirt do |domain|
#      domain.memory = 4096
#      domain.cpus = 2
#    end
#  end
#  config.vm.define "archlinux" do |archlinux|
#   archlinux.vm.box = "archlinux/archlinux"
#    archlinux.vm.synced_folder '.', '/vagrant', disabled: true
#  end
#  config.vm.define "freebsd" do |freebsd|
#    config.vm.box = "generic/freebsd11"
#  end
#  config.vm.define "openbsd" do |openbsd|
#    config.vm.box = "generic/openbsd6"
#  end
end
