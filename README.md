# Lazzurs Terragrunt

This is a Homebrew Tap to allow tfenv or terraform to be used with Terragrunt.

The default Homebrew Terragrunt package depends on Terraform and the current Homebrew policy is not to allow packages in core to have optional dependencies.

## How do I install these formulae?

First off if you have tfenv or Terragrunt already installed then please uninstall the current versions.

### Homebrew CLI

`brew install lazzurs/tfenv/terragrunt --without-terraform --with-tfenv`

### Bundle

```
tap 'lazzurs/terragrunt' || true
brew 'lazzurs/tfenv/terragrunt', args: ["without-terraform", "with-tfenv"]
```

## Documentation
`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
