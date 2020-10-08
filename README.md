# latex-box

Developer box for LaTeX


## Getting started

```
$ git clone --recursive https://github.com/extra2000/latex-box.git
$ cd latex-box
```


## Preparing environment

```
$ vagrant up --provider=libvirt
$ vagrant ssh latex-box -- sudo salt-call state.sls podman
$ vagrant ssh latex-box -- sudo salt-call state.sls latex
```
