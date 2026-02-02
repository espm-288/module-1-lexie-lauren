# Module 1: Tabular Data

## Project Overview

This module explores high-performance workflows for working with large tabular datasets using `duckdbfs`. The focus is on handling datasets that are larger than available RAM by leveraging DuckDB's streaming and remote file access capabilities.

## Case Study: Global Supply Chains (EXIOBASE 3.8.1)

This project analyzes [EXIOBASE 3.8.1](https://source.coop/youssef-harby/exiobase-3), a global Multi-Regional Input-Output (MRIO) database that tracks:
- Economic transactions between sectors and regions
- Environmental impacts (emissions, resource use, etc.)

### Dataset Details
- **Coverage**: 44 countries + 5 rest-of-world regions
- **Timeframe**: 1995–2022
- **Content**: Economic transactions (Z matrix), final demand (Y matrix), and environmental stressors (F matrix)
- **Format**: Cloud-optimized Parquet, partitioned by year and matrix type
- **Storage**: Hosted on Source Cooperative (S3)

## Getting Started

### Prerequisites
- R (version 4.0 or higher recommended)
- Required R packages:
  - `duckdbfs`
  - `dplyr`

### Installation

Install the required packages:
```r
install.packages("dplyr")
install.packages("duckdbfs")
```

## Usage

Open [tabular-data.qmd](tabular-data.qmd) in RStudio or another Quarto-compatible editor and follow the exercises:

1. **Exercise 1**: Connect to remote data without downloading
2. **Exercise 2**: Efficiently filter large datasets before loading into R
3. **Additional tasks**: Analyze CO2 emissions by sector

## Key Learning Objectives

- Work with datasets larger than RAM
- Connect to and query remote cloud-hosted data (S3)
- Apply efficient filtering strategies before data collection
- Leverage DuckDB's streaming capabilities through R
- Analyze environmental and economic data from MRIO databases

## Files

- `tabular-data.qmd`: Main Quarto document with exercises and analysis
- `README.md`: Project documentation (this file)

## Course Information

**Course**: ESPM 288  
**Module**: 1  
**Topic**: Working with larger-than-RAM data using duckdbfs

## License

This project is part of the ESPM 288 coursework.