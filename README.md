# snpxarray

Convert PySnpTools BED files to xarray DataArrays with full metadata support.

## Overview

This package provides a clean interface to convert genomic data from PySnpTools BED format into labeled xarray DataArrays, preserving all metadata including:

- Individual IDs (family ID, individual ID pairs)
- SNP positions (chromosome, genetic position, physical position)
- Proper genomic coordinate naming conventions

## Usage

See `snpxarray.ipynb` for a complete example of converting BED files to xarray format and saving to Zarr.

## Features

- **MultiIndex coordinates** for (family_id, individual_id) pairs
- **Genomic metadata** with bed-reader naming conventions
- **Zarr export** for efficient storage and lazy loading
- **Full PySnpTools compatibility**

## Installation

```bash
uv add snpxarray
```

## Dependencies

- xarray
- pysnptools  
- zarr

## License

MIT OR Apache-2.0
