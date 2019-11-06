# lidartoa

This script converts .asc files containing DTM/DSM maps into an Arnold .ass file and companion EXR files, for displacement map rendering.

The script is currently setup to parse .asc files specifically downloaded from https://data.gov.uk/dataset/80c522cc-e0bf-4466-8409-57a04c456197/lidar-composite-dsm-1m.

# Installation

```
pip install numpy
pip install OpenEXR
pip install PIL
```

# Usage

```
usage: lidartoa.py [-h] [--scale [SCALE]] path

Convert LIDAR DTM/DSM .asc files to EXR heightmap.

positional arguments:
  path                  input .asc file, or directory of .asc files

optional arguments:
  -h, --help            show this help message and exit
  --scale [SCALE], -s [SCALE]
                        (default is 1.0)
```
