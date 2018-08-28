# README

Manage your SSH like a boss

## Installation

Linux users can use the [installer](https://github.com/timonier/storm/blob/master/bin/installer):

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

## Contributing

1. Fork it.
2. Create your branch: `git checkout -b my-new-feature`.
3. Commit your changes: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin my-new-feature`.
5. Submit a pull request.

__Note__: Use the script `bin/build` to test your modifications locally.

If you like / use this project, please let me known by adding a [★](https://help.github.com/articles/about-stars/) on the [GitHub repository](https://github.com/timonier/storm).

## Links

* [emre/storm](https://github.com/emre/storm)
* [image "timonier/storm"](https://hub.docker.com/r/timonier/storm/)
* [timonier/dumb-entrypoint](https://github.com/timonier/dumb-entrypoint)
* [timonier/version-lister](https://github.com/timonier/version-lister)
