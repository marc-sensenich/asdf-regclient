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

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add regclient
# or
asdf plugin add regclient https://github.com/marc-sensenich/asdf-regclient.git
```

regclient:

```shell
# Show all installable versions
asdf list-all regclient

# Install specific version
asdf install regclient latest

# Set a version globally (on your ~/.tool-versions file)
asdf global regclient latest

# Now regclient commands are available
regclient --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/marc-sensenich/asdf-regclient/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Marc Sensenich](https://github.com/marc-sensenich/)
