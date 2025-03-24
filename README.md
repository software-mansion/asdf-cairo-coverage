# asdf-cairo-coverage

[cairo-coverage] plugin for the [asdf] version manager.

## Install

This plugin needs `bash`, `curl`, `tar` and other generic POSIX utilities.
Everything should be included by default on your system.

```shell
asdf plugin add cairo-coverage
```

or

```shell
asdf plugin add cairo-coverage https://github.com/software-mansion/asdf-cairo-coverage.git
```

## Use

Show all installable versions:

```shell
asdf list all cairo-coverage
```

Install latest version:

```shell
asdf install cairo-coverage latest
```

Install specific version:

```shell
asdf install cairo-coverage 0.2.0
```

Set a version globally (in your `~/.tool-versions` file):

```shell
asdf set --home cairo-coverage latest
```

Now cairo-coverage commands are available:

```shell
cairo-coverage --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to install & manage versions.

[asdf]: https://asdf-vm.com

[cairo-coverage]: https://github.com/software-mansion/cairo-coverage
