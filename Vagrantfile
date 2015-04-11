# -*- mode: ruby -*-
# vi: set ft=ruby :

$script = <<'SCRIPT'
# You can add PowerShell stuff here if you want...
echo "Executing script in Vagrantfile..."

# Install PyCharm Community (free version)
# choco install -y pycharm-community

# Install PyCharm Professional (paid version)
# choco install -y pycharm

# Install Python 3.4
# choco install -y python3

# Install PyPy
# choco install -y python.pypy

# Install IronPython
# choco install -y ironpython 

# Browse more chocolatey packages at https://chocolatey.org/packages
SCRIPT

Vagrant.configure(2) do |config|
  config.vm.box = "msabramo/HyperVServer2012R2PlusPython2"
  config.vm.provision "shell", inline: $script
end
