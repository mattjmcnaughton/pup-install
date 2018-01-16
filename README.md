# pup-install

[sheepdoge](https://github.com/mattjmcnaughton/sheepdoge) pup for managing
dependencies non-apt installations (currently snaps and bins). May eventually
split contents into their own top-level pups, but its not yet necessary.

## Variables

`pup-install` expects you to define the following variables:
- `pup_install_main_remotes_to_install`: List of dicts of bins to install and their
  locations.
- `pup_install_main_snaps_to_install`: List of snap packages to install.
