# homebrew-tap

♥️ A Homebrew tap to install CLI tools and other software from @tedilabs

## Usage

```sh
brew install --cask tedilabs/tap/<name>
```

Or tap first, then install by name:

```sh
brew tap tedilabs/tap
brew install --cask <name>
```

## Available casks

| Cask | Description |
|------|-------------|
| [`tfvault`](https://github.com/tedilabs/tfvault) | Universal Terraform credentials helper with pluggable secret backends |

## How it works

Casks under [`Casks/`](Casks/) are generated and committed
automatically by each project's release pipeline
([goreleaser](https://goreleaser.com)) whenever a new version is tagged.
Please do not edit them by hand — changes will be overwritten on the
next release. Issues and contributions belong in each project's own
repository.
