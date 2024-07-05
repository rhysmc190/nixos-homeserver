# NixOS homeserver

### Setup on new system
1. clone to ~/nixos-homeserver
1. `sudo mv /etc/nixos /etc/nixos.bak`
1. `sudo ln -s ~/nixos-homeserver /etc/nixos`
1. update hardware config from /etc/nixos.bak to ~/nixos-homeserver if necessary
1. `sudo nixos-rebuild switch`