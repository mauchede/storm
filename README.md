# README

Manage your SSH like a boss

⚠️ This project is no longer maintained. ⚠️

## Installation

```sh
# Define installation folder

export INSTALL_DIRECTORY=/usr/bin

# Use local installation

sudo bin/installer install

# Use remote installation

curl --location "https://github.com/timonier/storm/raw/master/bin/installer" | sudo sh -s -- install
```

__Note__: If you do not define `INSTALL_DIRECTORY`, `installer` will use in `/usr/local/bin`.

## Usage

Run the command `storm`:

```sh
# See all storm options

storm --help

# Run storm

storm add hostA morgan@1.1.1.1
# success  "hostA" updated successfully.
```

## Links

* [emre/storm](https://github.com/emre/storm)
* [image "timonier/storm"](https://hub.docker.com/r/timonier/storm/)
* [timonier/dumb-entrypoint](https://github.com/timonier/dumb-entrypoint)
* [timonier/version-lister](https://github.com/timonier/version-lister)
