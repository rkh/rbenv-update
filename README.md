This [rbenv](http://rbenv.org/) plugin adds the `rbenv update` command that updated rbenv and all installed plugins.

## Installation

Simply clone the repository into the plugins directory:

    [ -z "$RBENV_ROOT" ] && export RBENV_ROOT="$HOME/.rbenv"
    mkdir -p "$(rbenv root)/plugins"
    git clone https://github.com/rkh/rbenv-update.git "$(rbenv root)/plugins/rbenv-update"
