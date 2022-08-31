<div align="center">

# asdf-regclient [![Build](https://github.com/marc-sensenich/asdf-regclient/actions/workflows/build.yml/badge.svg)](https://github.com/marc-sensenich/asdf-regclient/actions/workflows/build.yml) [![Lint](https://github.com/marc-sensenich/asdf-regclient/actions/workflows/lint.yml/badge.svg)](https://github.com/marc-sensenich/asdf-regclient/actions/workflows/lint.yml)


[regclient](https://github.com/regclient/regclient/blob/main/docs/README.md) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash` and `curl`: generic POSIX utilities.

# Install

## Plugin

For installation you'll specify one of `regctl`, `regsync`, or `regbot` which correspond to the CLI tools published in https://github.com/regclient/regclient.

```shell
asdf plugin add regctl https://github.com/marc-sensenich/asdf-regclient.git
asdf plugin add regsync https://github.com/marc-sensenich/asdf-regclient.git
asdf plugin add regbot https://github.com/marc-sensenich/asdf-regclient.git
```

## regclient tools

Adjust `regctl` for the desired tool you've installed

```shell

# Show all installable versions
asdf list-all regctl

# Install specific version
asdf install regctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global regctl latest

# Now regclient commands are available
regctl --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](CONTRIBUTING.md).

[Thanks goes to these contributors](https://github.com/marc-sensenich/asdf-regclient/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Marc Sensenich](https://github.com/marc-sensenich/)
