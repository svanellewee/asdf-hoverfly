<div align="center">

# asdf-hoverfly [![Build](https://github.com/svanellewee/asdf-hoverfly/actions/workflows/build.yml/badge.svg)](https://github.com/svanellewee/asdf-hoverfly/actions/workflows/build.yml) [![Lint](https://github.com/svanellewee/asdf-hoverfly/actions/workflows/lint.yml/badge.svg)](https://github.com/svanellewee/asdf-hoverfly/actions/workflows/lint.yml)


[hoverfly]([]) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add hoverfly
# or
asdf plugin add hoverfly https://github.com/svanellewee/asdf-hoverfly.git
```

hoverfly:

```shell
# Show all installable versions
asdf list-all hoverfly

# Install specific version
asdf install hoverfly latest

# Set a version globally (on your ~/.tool-versions file)
asdf global hoverfly latest

# Now hoverfly commands are available
hoverfly --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/svanellewee/asdf-hoverfly/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Stephan van Ellewee](https://github.com/svanellewee/)
