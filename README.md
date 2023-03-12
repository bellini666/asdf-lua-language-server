<div align="center">

# asdf-lua-language-server [![Build](https://github.com/bellini666/asdf-lua-language-server/actions/workflows/build.yml/badge.svg)](https://github.com/bellini666/asdf-lua-language-server/actions/workflows/build.yml) [![Lint](https://github.com/bellini666/asdf-lua-language-server/actions/workflows/lint.yml/badge.svg)](https://github.com/bellini666/asdf-lua-language-server/actions/workflows/lint.yml)

[lua-language-server](https://github.com/LuaLS/lua-language-server) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `ASDF_LUA_LANGUAGE_SERVER_OVERRIDE_ARCH`: set this environment variable in
  your shell config to override the default architecture detection.

# Install

Plugin:

```shell
asdf plugin add lua-language-server
# or
asdf plugin add lua-language-server https://github.com/bellini666/asdf-lua-language-server.git
```

lua-language-server:

```shell
# Show all installable versions
asdf list-all lua-language-server

# Install specific version
asdf install lua-language-server latest

# Set a version globally (on your ~/.tool-versions file)
asdf global lua-language-server latest

# Now lua-language-server commands are available
lua-language-server --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](CONTRIBUTING.md).

[Thanks goes to these contributors](https://github.com/bellini666/asdf-lua-language-server/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Thiago Bellini Ribeiro](https://github.com/bellini666/)
