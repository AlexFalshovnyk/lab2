Vagrant.configure("2") do |config|
  config.vm.define "debian1" do |debian1|
    debian1.vm.box = "matthiasmullie/debian9-arm64"
  end

  config.vm.define "debian2" do |debian2|
    debian2.vm.box = "matthiasmullie/debian9-arm64"
  end

  
  config.vm.provider "Parallels" do |vb|
    vb.memory = 2048
  end
end
