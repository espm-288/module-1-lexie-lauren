# Module the First: Of Tables Most Tabular

## A Tale of Data Most Grand

Hark! This module doth explore the noble art of high-performance workflows for labouring with vast tabular datasets, employing the mighty `duckdbfs`. Our quest doth focus upon handling datasets that surpasseth the bounds of available RAM, by means of DuckDB's streaming magicks and remote file conjurations.

## A Case Most Studious: Of Global Supply Chains (EXIOBASE 3.8.1)

This undertaking doth analyze [EXIOBASE 3.8.1](https://source.coop/youssef-harby/exiobase-3), a global Multi-Regional Input-Output (MRIO) repository most wondrous, which tracketh:
- Economic transactions betwixt sectors and realms
- Environmental burdens (emissions, resource consumption, and such tribulations)

### Details of Yon Dataset
- **Coverage**: Two score and four countries, plus five rest-of-world dominions
- **Timeframe**: From the year of our Lord 1995 unto 2022
- **Content**: Economic transactions (the Z matrix), final demand (the Y matrix), and environmental stressors (the F matrix)
- **Format**: Cloud-optimized Parquet, partitioned by year and matrix most methodical
- **Storage**: Hosted upon Source Cooperative (that which men calleth S3)

## To Begin Thy Journey

### Prerequisites Most Necessary
- R (version 4.0 or higher, as it pleaseth thee)
- Required R packages of great import:
  - `duckdbfs`
  - `dplyr`

### Installation of Thy Tools

Install ye the required packages thus:
```r
install.packages("dplyr")
install.packages("duckdbfs")
```

## Upon Usage

Prithee, open [tabular-data.qmd](tabular-data.qmd) within RStudio or another editor most compatible with Quarto, and followeth these exercises:

1. **Exercise the First**: Connecteth to remote data without downloading, as if by sorcery
2. **Exercise the Second**: Filter efficiently yon large datasets ere loading them into R
3. **Additional labours**: Analyze CO2 emissions by sector most diligently

## Objectives of Learning Most Key

- To work with datasets larger than RAM, as Hamlet's ambition
- To connect unto and query remote cloud-hosted data (S3), as distant as the stars
- To apply efficient filtering stratagems before data collection
- To leverage DuckDB's streaming capabilities through R, swift as Mercury
- To analyze environmental and economic data from MRIO repositories most thoroughly

## Files of Import

- `tabular-data.qmd`: The principal Quarto document, wherein lie exercises and analysis
- `tabular-data.pdf`: PDF rendering of the tabular data analysis
- `tabular-data.html`: [HTML rendering of tabular data analysis](https://espm-288.github.io/module-1-lexie-lauren/tabular-data.html)
- `example2.qmd`: Additional analysis document (without dash)
- `example2.html`: [HTML rendering of example2 analysis](https://espm-288.github.io/module-1-lexie-lauren/example2.html)
- `example-2.qmd`: Additional analysis document (with dash)
- `example-2.html`: [HTML rendering of example-2 analysis](https://espm-288.github.io/module-1-lexie-lauren/example-2.html)
- `example-2.pdf`: PDF rendering of example-2 analysis
- `README.md`: Documentation of this project (this very parchment thou readest)

## Contributions of the Team

This project was crafted through collaborative effort betwixt Lauren and Lexie, each bringing their talents to bear:

- **Lauren**: Primary creator of the `example2` file series (example2.qmd, example2.html) and the `tabular-data.pdf`
- **Lexie**: Primary creator of the `example-2` file series (example-2.qmd, example-2.html, example-2.pdf)

All labor was performed collaboratively, and most files bear the marks of edits from both team members, as befits true partnership in scholarly pursuit.

## Information Regarding the Course

**Course**: ESPM 288  
**Module**: The First  
**Topic**: Working with data larger than RAM, using the noble duckdbfs

## License Most Fair

This project doth form part of the ESPM 288 coursework, and is bound thereby.