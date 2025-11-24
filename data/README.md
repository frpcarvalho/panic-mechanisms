# Data Directory

## NHANES Data
This project uses publicly available data from NHANES 1999-2004.

**Download from:** https://www.cdc.gov/nchs/nhanes/

## Directory Structure
- `raw/` - Original NHANES data files (not tracked in git)
- `processed/` - Cleaned datasets (not tracked in git)
- `examples/` - Small example datasets for testing

## Note
Large data files are not tracked in git. Download instructions:
1. Visit NHANES website
2. Download cycles 1999-2000, 2001-2002, 2003-2004
3. Place files in `data/raw/`
4. Run `notebooks/01_data_preparation.ipynb`
