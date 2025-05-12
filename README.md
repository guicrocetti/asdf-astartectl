<div align="center">

# asdf-astartectl [![Build](https://github.com/guicrocetti/asdf-astartectl/actions/workflows/build.yml/badge.svg)](https://github.com/guicrocetti/asdf-astartectl/actions/workflows/build.yml) [![Lint](https://github.com/guicrocetti/asdf-astartectl/actions/workflows/lint.yml/badge.svg)](https://github.com/guicrocetti/asdf-astartectl/actions/workflows/lint.yml)

[astartectl](https://github.com/astarte-platform/astartectl) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add astartectl
# or
asdf plugin add astartectl https://github.com/guicrocetti/asdf-astartectl.git
```

astartectl:

```shell
# Show all installable versions
asdf list-all astartectl

# Install specific version
asdf install astartectl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global astartectl latest

# Now astartectl commands are available
astartectl version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/guicrocetti/asdf-astartectl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Guilherme Crocetti](https://github.com/guicrocetti/)
