# latex-box

Developer box for LaTeX


## Getting started

```
$ git clone --recursive https://github.com/extra2000/latex-box.git
$ cd latex-box
```


## Preparing environment

Choose one of Vagrant files from `vagrant/examples/`. For example:
```
$ cp vagrant/examples/Vagrantfile.latex-box.fedora-33.x86_64.example vagrant/Vagrantfile.latex-box
```

Create Vagrant box and then provision it:
```
$ vagrant up --provider=libvirt
$ vagrant ssh latex-box -- sudo salt-call state.highstate
$ vagrant ssh latex-box -- sudo salt-call state.sls latex
```
