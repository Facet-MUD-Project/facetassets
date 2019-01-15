# FacetAssets

Shared assets for the various FacetMUD implementations.

This repo contains the reference world which all implementations must be able to
render. It also contains the specifications to which all implementations must
conform.

## Data format

All assets (rooms, objects, etc) are created in the `TOML` format. This is meant
to allow a simple, language-neutral data specification without all the bells and
whistles, or security considerations, of other markup formats.

All "hooks" and scripting which is done in these assets is written in the Lua
language. This means that every implementation of the Facet MUD must be able to
run Lua scripts.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for information on how to contribute.

## Code of Conduct

See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

## Maintainers

Our primary maintainers are:

* @tarkatronic
* @daftpun

## Contributors

Coming soon: https://github.com/all-contributors/all-contributors
