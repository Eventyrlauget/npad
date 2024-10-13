# how to use this config first time
- install nixOs with gui
- boot fresh nixos
- download this repo, or at least the configuration.nix
- copy config from this repo to fresh install to enable flakes and git: `sudo cp ./configuration.nix /etc/nixos/configuration.nix`
- quick rebuild: `sudo nixos-rebuild switch`
- now you can use flakes to update: `sudo nixos-rebuild switch --flake .#npad`


## Tips: 
start a program found from https://search.nixos.org/packages

- `nix run nixpkgs#localsend`

get a shell with python:

- `nix shell nixpkgs#python3`
