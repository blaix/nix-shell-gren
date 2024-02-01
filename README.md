# Nix Shell Template for Gren

This is a template to use [gren](https://gren-lang.org/)
in an isolated [nix shell](https://nixos.wiki/wiki/Development_environment_with_nix-shell)
that automatically loads with [direnv](https://direnv.net/).

## Requirements

* [nix](https://nix.dev/install-nix.html)
* [direnv](https://direnv.net/)
* Optional but highly recommended: [nix-direnv](https://github.com/nix-community/nix-direnv)

## Usage

1. Copy this repo. E.g. with [degit](https://github.com/Rich-Harris/degit):
  `degit blaix/nix-shell-gren my-gren-project`
2. `cd my-gren-project`
3. `direnv allow`
4. `gren init` 🎉
