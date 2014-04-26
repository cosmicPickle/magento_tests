Vagrant.configure("2") do |config|
  config.vm.box = "hashicorp/precise32"
  config.vm.synced_folder ".", "/vagrant", {:mount_options => ['dmode=777','fmode=777']}
end