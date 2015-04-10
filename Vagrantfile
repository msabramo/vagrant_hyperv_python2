# -*- mode: ruby -*-
# vi: set ft=ruby :

$script = <<'SCRIPT'
# You can add PowerShell stuff here if you want...
echo "Executing script in Vagrantfile..."

# Install git
# choco install -y git

# Install PuTTY (http://www.chiark.greenend.org.uk/~sgtatham/putty/)
# choco install -y putty

# Browse more chocolatey packages at https://chocolatey.org/packages
SCRIPT

Vagrant.configure(2) do |config|
  config.vm.box = "msabramo/HyperVServer2012"
  config.vm.provision "shell", inline: $script
end
