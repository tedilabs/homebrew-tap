# homebrew-tap

♥️ A Homebrew tap to install CLI tools and other software from @tedilabs

## Usage

```sh
brew install tedilabs/tap/<formula>
```

Or tap first, then install by name:

```sh
brew tap tedilabs/tap
brew install <formula>
```

## Available formulae

| Formula | Description |
|---------|-------------|
| [`ota`](https://github.com/tedilabs/ota) | k9s-style terminal UI for Okta Workforce Identity (macOS and Linux) |
| [`tfvault`](https://github.com/tedilabs/tfvault) | Universal Terraform credentials helper with pluggable secret backends (macOS and Linux) |

## How it works

Formulae under [`Formula/`](Formula/) are generated and committed
automatically by each project's release pipeline whenever a new version
is tagged. Please do not edit them by hand — changes will be
overwritten on the next release. Issues and contributions belong in
each project's own repository.
