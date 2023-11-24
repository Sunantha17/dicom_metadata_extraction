# DICOM Metadata Extractor

This script extracts metadata from a collection of DICOM files and creates a CSV file with the metadata.

## Overview

DICOM (Digital Imaging and Communications in Medicine) is a standard for storing, transmitting, and sharing medical images. This script uses the `pydicom` library to read DICOM files and extracts metadata attributes, excluding the pixel data and patient name for privacy reasons.

## Requirements

- Python 3.x
- NumPy
- Pandas
- Pydicom
- tqdm

Install the required packages using:

```bash
pip install numpy pandas pydicom tqdm
