# Changelog

## [2.0.0](https://github.com/extra2000/latex-box/compare/v1.0.0...v2.0.0) (2021-01-21)


### ⚠ BREAKING CHANGES

* **vagrant, gitignore:** Vagrant file `Vagrantfile.latex-box` has been removed by default. User need to manually copy one of Vagrant files from `vagrant/examples/`.

### Features

* **salt:** Add `swapoff` state into `state.highstate` ([918b10c](https://github.com/extra2000/latex-box/commit/918b10c214b8638a5b720462391ee7860348113c))
* **submodule:** Add `cockpit-formula` ([0b80389](https://github.com/extra2000/latex-box/commit/0b80389a237413fe459c9fe0beba523baf5f324e))
* **submodule:** Update `latex-formula` to [v2.0.0](https://github.com/extra2000/latex-formula/releases/tag/v2.0.0) ([1dc2d87](https://github.com/extra2000/latex-box/commit/1dc2d8755530635653b77600994dc8b7ba6f662e))
* **submodule:** Update `podman-formula` to [v2.2.1](https://github.com/extra2000/podman-formula/releases/tag/v2.2.1) ([fc8ce02](https://github.com/extra2000/latex-box/commit/fc8ce021d4cea8aad3a7b24461508a492ac95035))
* **vagrant:** Allow multiple vagrant files in `vagrant/` ([399eb2a](https://github.com/extra2000/latex-box/commit/399eb2a6d0c8fd4d1a811cbb4a4eb6f70f52ba10))
* **vagrant:** Import Vagrant files from [extra2000/generic-box v1.4.1](https://github.com/extra2000/generic-box/releases/tag/v1.4.1) ([6dbc253](https://github.com/extra2000/latex-box/commit/6dbc25320328300dd4b475b51d9c5d0868de9eba))


### Code Refactoring

* **salt:** Add `state.highstate` ([252caa6](https://github.com/extra2000/latex-box/commit/252caa686fe022bd51f6f962b81072696bd26712))
* **salt/roots/pillar/latex.sls:** Put all dicts into `lookup` ([65794ba](https://github.com/extra2000/latex-box/commit/65794bafbd7d83836ea5fa77df726d98135430e9))
* **vagrant, gitignore:** Remove `Vagrantfile.latex-box` so that user can customize Vagrant box without affecting git commit ([e54007b](https://github.com/extra2000/latex-box/commit/e54007b0896262b722c9bfcaa910af14ac70d942))


### Documentations

* **README:** Add badges ([e2d9f38](https://github.com/extra2000/latex-box/commit/e2d9f3801334aa67a312ef6820964bd9a09e84fd))
* **README:** Add instruction to copy one of Vagrant file examples ([73a984e](https://github.com/extra2000/latex-box/commit/73a984e5156adac8f46c573efe48efd044e73c01))
* **README:** Add latex state after high state ([9abd4ab](https://github.com/extra2000/latex-box/commit/9abd4ab904f1faf670093a7a0e39f4ecbf149403))
* **README:** Update instruction to use `state.highstate` ([da1aa8f](https://github.com/extra2000/latex-box/commit/da1aa8fd8f45910f96493895be7bc897b287df74))


### Continuous Integrations

* **appveyor:** Update `build_script` instructions ([0f101ec](https://github.com/extra2000/latex-box/commit/0f101ecd74bf23f8326870fcc2d778b871b0ef4d))
* **AppVeyor:** Add `semantic-release` ([aace923](https://github.com/extra2000/latex-box/commit/aace92356f2676e90b576a1f91c4270207387c75))
* **AppVeyor:** Upgrade Ubuntu from `18.04` to `20.04` ([22c35b2](https://github.com/extra2000/latex-box/commit/22c35b2495848e02df464f18d3f6b3f78f8d2514))
* **semantic-release:** Write version into `VERSION.txt` file ([ceadac4](https://github.com/extra2000/latex-box/commit/ceadac46c9cc997f3eb8c50c375ebaf96b0d0162))
* Remove Travis CI because it is no longer free ([de589fa](https://github.com/extra2000/latex-box/commit/de589fa7825e10ecb0b16f8d019e830e34eab26d))

## 1.0.0 (2020-10-08)


### Continuous Integrations

* **semantic-release:** Fix patch updates with BREAKING CHANGE doesn't trigger major release ([a7c3b35](https://github.com/extra2000/latex-box/commit/a7c3b35172e73fee948e26d4a1e196f16cffe5a1))
