# Packer ZSH Completion

This is a basic ZSH completion file for [Packer](http://www.packer.io/).

Usage
=====

To install in [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) clone this repo:

    $ git clone https://github.com/gunzy83/packer-zsh-completion.git ~/.oh-my-zsh/plugins/packer

Remember to add packer to the plugins list in ~/.zshrc.

# Installation

## oh-my-zsh

1. Get it

    Clone into custom plugins directory:

    ```sh
    $ git clone https://github.com/gunzy83/packer-zsh-completion.git ~/.oh-my-zsh/plugins/packer
    ```

2. Include it

    Then add the plugin to your plugin list in oh-my-zsh configuration:

    ```sh
    $ $EDITOR ~/.zshrc

    # -plugins=(...)
    # +plugins=(... packer)
    ```


## antigen

1. Add `antigen bundle gunzy83/packer-zsh-completion` to your `.zshrc` with your other antigen bundle commands.


## zgen

1. Add `zgen load gunzy83/packer-zsh-completion` to your `.zshrc`
2. Regenerate your `init.zsh` with `zgen save`


# Usage

After installation re-source your `.zshrc`.


# Future Plans

* Add true/false options for -parallel
* Add parsing of .json files to find builders for -except and -only

# License

**packer-zsh-completion** is provided under the terms of [The MIT License](http://opensource.org/licenses/MIT)

Copyright &copy; 2014, [Ross Williams](mailto:gunzy83au@gmail.com)