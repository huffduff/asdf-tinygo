<div align="center">

# asdf-tinygo [![Build](https://github.com/tommyo/asdf-tinygo/actions/workflows/build.yml/badge.svg)](https://github.com/tommyo/asdf-tinygo/actions/workflows/build.yml) [![Lint](https://github.com/tommyo/asdf-tinygo/actions/workflows/lint.yml/badge.svg)](https://github.com/tommyo/asdf-tinygo/actions/workflows/lint.yml)

[tinygo](https://tinygo.org/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add tinygo
# or
asdf plugin add tinygo https://github.com/tommyo/asdf-tinygo.git
```

tinygo:

```shell
# Show all installable versions
asdf list-all tinygo

# Install specific version
asdf install tinygo latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tinygo latest

# Now tinygo commands are available
tinygo version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tommyo/asdf-tinygo/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tom O'Reilly](https://github.com/tommyo/)
