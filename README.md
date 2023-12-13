<div align="center">

# asdf-radius-app

[![Build](https://github.com/daveneeley/asdf-radius-app/actions/workflows/build.yml/badge.svg)](https://github.com/daveneeley/asdf-radius-app/actions/workflows/build.yml) [![Lint](https://github.com/daveneeley/asdf-radius-app/actions/workflows/lint.yml/badge.svg)](https://github.com/daveneeley/asdf-radius-app/actions/workflows/lint.yml)

[radius](https://github.com/radius-project/radius) plugin for the [asdf version manager](https://asdf-vm.com). Documentation at [radapp.io](https://radapp.io/).

</div>

# Contents

- [asdf-radius-app](#asdf-radius-app)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `sha256sum`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add radius-app
# or
asdf plugin add radius-app https://github.com/daveneeley/asdf-radius-app.git
```

radius-app:

```shell
# Show all installable versions
asdf list-all radius-app

# Install specific version
asdf install radius-app latest

# Set a version globally (on your ~/.tool-versions file)
asdf global radius-app latest

# Now radius-app commands are available
rad --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/daveneeley/asdf-radius-app/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Dave Neeley](https://github.com/daveneeley/)
