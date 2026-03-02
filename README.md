# Noahh Command Line
Command-line utilities for working with [Noahh SDK](https://noahh-sdk.org).

For more information see its [page on the docs](https://docs.noahh-sdk.org/getting-started/noahh-cli).

## Usage
The CLI is typically invoked for you by Noahh's build system, but it does have some standalone features:

``` bash
# Walks you through creating a Noahh mod via a template
noahh new

# Runs Geometry Dash from the default profile
noahh run

# Installs the sdk. For more info see the docs
noahh sdk install

# Uploads a mod to the index. For more info see the docs
noahh index mods create
```

## Installation
*(For more in depth information see the docs.)*

[![Packaging status](https://repology.org/badge/vertical-allrepos/noahh-sdk-cli.svg)](https://repology.org/project/noahh-sdk-cli/versions)

### Windows (scoop)
```
scoop bucket add extras
scoop install noahh-sdk-cli
```

### Windows (Winget)
> This may be out of date. Sorry!
```
winget install NoahhSDK.NoahhCLI
```

### MacOS (brew)
```
brew install noahh-sdk/noahh/noahh-cli
```

### Linux
We provide linux binaries [in every release](https://github.com/noahh-sdk/cli/releases/latest).

### Arch Linux (Unofficial AUR package)
> **Note**: This package is unofficial and not maintained by us. Use at your own risk.

[noahh-cli-bin](https://aur.archlinux.org/packages/noahh-cli-bin)

### From source
> **Note**: This requires a [local rust installation](https://www.rust-lang.org/tools/install), and may take a very long time
```
cargo install --git https://github.com/noahh-sdk/cli
```

