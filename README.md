<div align="center">

# asdf-updatecli [![Build](https://github.com/updatecli/asdf-updatecli/actions/workflows/build.yml/badge.svg)](https://github.com/updatecli/asdf-updatecli/actions/workflows/build.yml) [![Lint](https://github.com/updatecli/asdf-updatecli/actions/workflows/lint.yml/badge.svg)](https://github.com/updatecli/asdf-updatecli/actions/workflows/lint.yml)

[updatecli](https://www.updatecli.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-updatecli  ](#asdf-updatecli--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add updatecli
# or
asdf plugin add updatecli https://github.com/updatecli/asdf-updatecli.git
```

updatecli:

```shell
# Show all installable versions
asdf list-all updatecli

# Install specific version
asdf install updatecli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global updatecli latest

# Now updatecli commands are available
updatecli version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/updatecli/asdf-updatecli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Updatecli](https://github.com/updatecli/)
