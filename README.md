# HOL-Light Installation on Mac Book 

** Origianl Source: https://sourceforge.net/p/hol/mailman/message/32839431/


Install Nix.  Follow the instructions from the nix manual (http://nixos.org/nix/manual).  
Basically you have to type the following

> $ bash <(curl https://nixos.org/nix/install)

> source /usr/local/etc/profile.d/nix.sh

> nix-channel --add http://nixos.org/channels/nixpkgs-unstable

> nix-channel --update

> nix-env -i hol_light

Finally you can load hol-light from anywhere by 

> hol_light
