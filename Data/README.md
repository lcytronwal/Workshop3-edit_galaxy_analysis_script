# Data Directory

This directory contains galaxy property datasets from the Portsmouth Group, used for analyzing and exploring galaxy classifications and properties. For more information, see https://www.sdss4.org/dr17/spectro/galaxy_portsmouth/

## Files

### Random-AGN-Galaxies-PortsmouthGroup_properties.csv
- **Description**: Dataset containing properties of random Active Galactic Nuclei (AGN) galaxies
- **Size**: 113,760 bytes
- **Records**: ~500 entries

### Random-SB-Galaxies-PortsmouthGroup_properties.csv
- **Description**: Dataset containing properties of random Starburst (SB) galaxies
- **Size**: 119,765 bytes
- **Records**: ~500 entries

### Random-SF-Galaxies-PortsmouthGroup_properties.csv
- **Description**: Dataset containing properties of random Star-Forming (SF) galaxies
- **Size**: 122,698 bytes
- **Records**: ~500 entries

## Data Format

All datasets are CSV (Comma-Separated Values) files with the following columns:

- `objid`: Unique object identifier
- `ra`: Right ascension coordinate
- `dec`: Declination coordinate
- `petror90_r`: Petrosian radius at 90% light in r-band
- `g`: g-band magnitude
- `r`: r-band magnitude
- `i`: i-band magnitude
- `z`: z-band magnitude
- `subClass`: Galaxy classification (AGN, SB, or SF)
- `logMass`: Log of galaxy mass (in solar masses)
- `SFR`: Star formation rate

## Usage

These datasets are used as input for `galaxies_analysis.py` to:
- Read and parse galaxy properties
- Explore galaxy characteristics by classification
- Analyze relationships between galaxy properties
- Perform statistical analysis on different galaxy populations

## Galaxy Classifications

- **AGN** (Active Galactic Nuclei): Galaxies with active supermassive black holes at their centers
- **SB** (Starburst): Galaxies undergoing intense star formation
- **SF** (Star-Forming): Regular galaxies with ongoing star formation

## Source

All data originates from the Portsmouth Group galaxy survey.
