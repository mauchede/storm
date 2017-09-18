# README

Manage your SSH like a boss

## Installation

Copy `bin/storm` into your executable folder (like `/usr/local/bin` or `$HOME/bin`):

```sh
sudo curl --location --output /usr/local/bin/storm "https://github.com/timonier/storm/raw/master/bin/storm"
sudo chmod +x /usr/local/bin/storm
```

Linux users can use the [installer](https://github.com/timonier/storm/blob/master/bin/installer):

```sh
curl --location "https://github.com/timonier/storm/raw/master/bin/installer" | sudo sh -s -- install
```

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

## Links

* [emre/storm](https://github.com/emre/storm)
* [image "timonier/storm"](https://hub.docker.com/r/timonier/storm/)
* [timonier/dumb-entrypoint](https://github.com/timonier/dumb-entrypoint)
* [timonier/version-lister](https://github.com/timonier/version-lister)
