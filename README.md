# meta-phyhub

Yocto layer for the phyHUB platform.

The layer contains all the tools to connect your Yocto device to the phyHUB
platform.

## Dependencies

- URI: https://git.openembedded.org/openembedded-core
  - branch: scarthgap
  - revision: HEAD

## Branches

| Branch          | Yocto Release |
|-----------------|---------------|
| scarthgap       | 5.0 (scarthgap) |
| master          | next release (development) |

## Usage

Add this layer to your `bblayers.conf`:

```
BBLAYERS += "/path/to/meta-phyhub"
```

## License

All metadata is MIT licensed unless otherwise stated.
See `LICENSE.MIT` for the full license text.
