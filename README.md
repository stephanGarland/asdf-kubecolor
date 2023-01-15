<div align="center">

# asdf-kubecolor [![Build](https://github.com/stephanGarland/asdf-kubecolor/actions/workflows/build.yml/badge.svg)](https://github.com/stephanGarland/asdf-kubecolor/actions/workflows/build.yml) [![Lint](https://github.com/stephanGarland/asdf-kubecolor/actions/workflows/lint.yml/badge.svg)](https://github.com/stephanGarland/asdf-kubecolor/actions/workflows/lint.yml)


[kubecolor](https://github.com/stephanGarland/asdf-kubecolor) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add kubecolor
# or
asdf plugin add kubecolor https://github.com/stephanGarland/asdf-kubecolor.git
```

kubecolor:

```shell
# Show all installable versions
asdf list-all kubecolor

# Install specific version
asdf install kubecolor latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kubecolor latest

# Now kubecolor commands are available
kubecolor --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/stephanGarland/asdf-kubecolor/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Stephan Garland](https://github.com/stephanGarland/)
