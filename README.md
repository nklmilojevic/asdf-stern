<div align="center">

# asdf-stern [![Build](https://github.com/nklmilojevic/asdf-stern/actions/workflows/build.yml/badge.svg)](https://github.com/nklmilojevic/asdf-stern/actions/workflows/build.yml) [![Lint](https://github.com/nklmilojevic/asdf-stern/actions/workflows/lint.yml/badge.svg)](https://github.com/nklmilojevic/asdf-stern/actions/workflows/lint.yml)


[stern](https://github.com/stern/stern) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add stern
# or
asdf plugin add stern https://github.com/nklmilojevic/asdf-stern.git
```

stern:

```shell
# Show all installable versions
asdf list-all stern

# Install specific version
asdf install stern latest

# Set a version globally (on your ~/.tool-versions file)
asdf global stern latest

# Now stern commands are available
stern -version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nklmilojevic/asdf-stern/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Nikola Milojević](https://github.com/nklmilojevic/)
