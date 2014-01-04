# dokku-plugin-volume

A plugin for dokku which lets dokku containers have an lvm volume
mounted from the host.

Useful for small scale hosting of things which want a data directory
(e.g. wordpress, phpbb, mediawiki)

# Installation

Just clone this repository, and symlink it into your dokku plugins folder

E.g.

    cd /usr/local
    sudo git clone https://github.com/bobtfish/dokku-plugin-volume.git
    sudo ln -s /usr/local/dokku-plugin-volume /var/lib/dokku/plugins/volume

# Usage

TODO - once this actually works ;)

# Copyright and License

Copyright Tomas Doran 2014.

MIT Licensed.

