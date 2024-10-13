# how to use this config first time
- install nixOs with gui
- boot fresh nixos
- download this repo, or at least the configuration.nix
- copy config from this repo to fresh install to enable flakes and git: `sudo cp ./configuration.nix /etc/nixos/configuration.nix`
- quick rebuild: `sudo nixos-rebuild switch`
- now you can use flakes to update: `sudo nixos-rebuild switch --flake .#npad`
