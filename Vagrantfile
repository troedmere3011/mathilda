Vagrant.configure("2") do |config|
    config.vm.box = "generic/ubuntu1804"

    config.vm.define 'ubuntu'

    # Prevent SharedFoldersEnableSymlinksCreate errors
    config.vm.synced_folder ".", "/vagrant", disabled: true
    config.vm.provider "virtualbox" do |v|
        v.memory = 5048
        v.cpus = 4
        v.gui = false
    end

end
