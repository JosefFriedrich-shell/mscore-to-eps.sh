[![Build Status](https://travis-ci.org/Josef-Friedrich/mscore-to-eps.sh.svg?branch=master)](https://travis-ci.org/Josef-Friedrich/mscore-to-eps.sh)

# mscore-to-eps.sh


## Summary / Short description

> Convert MuseScore files (*.mscz, *.mscx) to the EPS file format.

## Usage

```
Usage: mscore-to-eps.sh [-hnsv] [<path>]

Convert MuseScore files (*.mscz, *.mscx) to the EPS file format.

Convert MuseScore files to eps using 'pdfcrop' and 'pdftops' or
'Inkscape'. If <path> is omitted, all MuseScore files in the
current working directory are converted. <path> can be either a
directory or a MuseScore file.

DEPENDENCIES
	'pdfcrop' (included in TeXlive) and 'pdftops' (Poppler tools) or
	'Inkscape'

OPTIONS
	-h, --help
	  Show this help message.
	-n, --no-clean
	  Do not remove / clean intermediate *.pdf files
	-s, --short-description
	  Show a short description / summary.
	-v, --version
	  Show the version number of this script.

```

## Project pages

* https://github.com/Josef-Friedrich/mscore-to-eps.sh

## Testing

```
make test
```

