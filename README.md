
# Tomlson

Tomlson is a lightweight Neovim configuration framework. It is designed to be
simple and fast, while still providing the features that you need to make
Neovim as powerful as possible.

## Installation

To install Tomlson, simply clone the repository and run `make install`. This
will copy the necessary files into your Neovim configuration directory.

## Usage

Tomlson is designed to be used in conjunction with a configuration file. When
Neovim is started, Tomlson will automatically load the configuration file and
apply the settings and plugins that are specified.

The configuration file is a TOML file, and is located in the `config/`
directory. It should be named `config.toml`.

## Plugins

Tomlson supports plugins, which can be installed via the `packer` plugin
manager. Plugins should be placed in the `plugin/` directory.

## License

Tomlson is released under the MIT License. See the LICENSE file for more
details.