# rbenv installer

This tool is used to install `rbenv` and some plugins. It also provides 
scripts to install required software to be able to compile **Ruby**.

Forked from [fesplugas/rbenv-installer](https://github.com/fesplugas/rbenv-installer).


## Requirements

- Git
- Curl


## Install

Install [rbenv] and friends by running:

    curl https://raw.github.com/Oshuma/rbenv-installer/master/bin/rbenv-installer | bash


## Installing a Ruby

Install Ruby `1.9.3-p392` and make it global:

    rbenv install 1.9.3-p392
    rbenv global 1.9.3-p392


## Updating

Update `rbenv` and plugins provided by the installer running:

    rbenv update


## About rbenv

**rbenv** source code is available at <https://github.com/sstephenson/rbenv>

[rbenv]: https://github.com/sstephenson/rbenv
