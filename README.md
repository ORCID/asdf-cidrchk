<div align="center">

# asdf-cidrchk [![Build](https://github.com/ORCID/asdf-cidrchk/actions/workflows/build.yml/badge.svg)](https://github.com/ORCID/asdf-cidrchk/actions/workflows/build.yml) [![Lint](https://github.com/ORCID/asdf-cidrchk/actions/workflows/lint.yml/badge.svg)](https://github.com/ORCID/asdf-cidrchk/actions/workflows/lint.yml)


[cidrchk](https://github.com/mhausenblas/cidrchk) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add cidrchk https://github.com/ORCID/asdf-cidrchk.git
```

cidrchk:

```shell
# Show all installable versions
asdf list-all cidrchk

# Install specific version
asdf install cidrchk latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cidrchk latest

# Now cidrchk commands are available
cidrchk --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

