<div align="center">

# asdf-headlamp [![Build](https://github.com/zmjolk/asdf-headlamp/actions/workflows/build.yml/badge.svg)](https://github.com/zmjolk/asdf-headlamp/actions/workflows/build.yml) [![Lint](https://github.com/zmjolk/asdf-headlamp/actions/workflows/lint.yml/badge.svg)](https://github.com/zmjolk/asdf-headlamp/actions/workflows/lint.yml)

[headlamp](https://headlamp.dev/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add headlamp # not on shortname listing yet
# or
asdf plugin add headlamp https://github.com/zmjolk/asdf-headlamp.git
```

headlamp:

```shell
# Show all installable versions
asdf list-all headlamp

# Install specific version
asdf install headlamp latest

# Set a version globally (on your ~/.tool-versions file)
asdf global headlamp latest

# Now headlamp commands are available
headlamp --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/zmjolk/asdf-headlamp/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jack Scott](https://github.com/zmjolk/)
