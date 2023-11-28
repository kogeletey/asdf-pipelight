<div align="center">

# asdf-pipelight [![Build](https://github.com/kogeletey/asdf-pipelight/actions/workflows/build.yml/badge.svg)](https://github.com/kogeletey/asdf-pipelight/actions/workflows/build.yml) [![Lint](https://github.com/kogeletey/asdf-pipelight/actions/workflows/lint.yml/badge.svg)](https://github.com/kogeletey/asdf-pipelight/actions/workflows/lint.yml)

[pipelight](ttps://pipelight.dev/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`,`zstd`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

If you have a Debian system like Ubuntu, you can install it by typing

```shell
apt install zstd
```

# Install

Plugin:

```shell
asdf plugin add pipelight
# or
asdf plugin add pipelight https://github.com/kogeletey/asdf-pipelight.git
```

pipelight:

```shell
# Show all installable versions
asdf list-all pipelight

# Install specific version
asdf install pipelight latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pipelight latest

# Now pipelight commands are available
pipelight --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/kogeletey/asdf-pipelight/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Konrad Geletey](https://github.com/kogeletey/)
