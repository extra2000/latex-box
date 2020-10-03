# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vagrant.plugins = ["vagrant-reload", "vagrant-scp"]
end

latex_box_vagrantfile = './vagrant/Vagrantfile.latex-box'
load latex_box_vagrantfile if File.exists?(latex_box_vagrantfile)
