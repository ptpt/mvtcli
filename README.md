# mvtcli

Command line for encoding and decoding [Mapbox Vector Tiles](https://github.com/mapbox/vector-tile-spec).

![PyPI - Version](https://img.shields.io/pypi/v/mvtcli)

## Installation

```shell
pip install mvtcli
```

## Examples

Decode:

```shell
curl 'https://tiles.mapillary.com/maps/vtp/mly1/2/1/0/0?access_token=YOUR_TOKEN' -o /tmp/tile.mvt
uvx mvtcli decode < /tmp/tile.mvt
```

Encode:

```shell
TBD
```
