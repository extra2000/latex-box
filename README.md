# latex-box

| License | Versioning | Build |
| ------- | ---------- | ----- |
| [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) | [![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release) | [![Build status](https://ci.appveyor.com/api/projects/status/g3i7ayqoliim0da4/branch/master?svg=true)](https://ci.appveyor.com/project/nikAizuddin/latex-box/branch/master) |

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
