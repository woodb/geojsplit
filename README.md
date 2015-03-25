# geojsplit

Split GeoJSON files into smaller pieces.

## Installation

```
$ npm -g install geojsplit
```

## Usage
```
$ geojsplit --help
```

    Usage: geojsplit [-a suffix_length] [-l geometry_count] filename

    Version: 0.0.2

    Similar to UNIX split, geojsplit splits up a GeoJSON file into smaller
    GeoJSON files. Unlike UNIX split, files cannot simply be concatonated
    back again.

    Options:
      -a, --suffix-length     number of characters in the suffix length for split file names
      -l, --geometry-count    number of geometries per split file
      --help, -h              display this message
      -v, --verbose           verbose output
      -k, --key               key to use to split Features into files (state ID, for example)
      -o, --output-directory  put files into this dir
