Vagrant.configure("2") do |config|
  config.vm.box = "debian/buster64"
  config.vm.provision :ansible do |ansible|
    ansible.compatibility_mode = "2.0"
    ansible.playbook = "site.yml"
  end
end
