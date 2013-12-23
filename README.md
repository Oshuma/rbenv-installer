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

## fish shell

```fish
# ~/.config/fish/config.fish
set -x RBENV_ROOT $HOME/.rbenv

if test -d $RBENV_ROOT
  set -x PATH $RBENV_ROOT/bin $PATH
  status --is-interactive; and . (rbenv init -|psub)
end
```


## Installing a Ruby

Install Ruby `ruby-2.0.0-p353` and make it global:

    rbenv install ruby-2.0.0-p353
    rbenv global ruby-2.0.0-p353


## Updating

Update `rbenv` and plugins provided by the installer running:

    rbenv update


## About rbenv

**rbenv** source code is available at <https://github.com/sstephenson/rbenv>

[rbenv]: https://github.com/sstephenson/rbenv
