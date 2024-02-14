# Alaskapox

## Contents

This repository aims to provide decision makers, researchers, and the public with comprehensive and timely data on the Alaskapox virus, including confirmed, suspected, and discarded cases. The data are collected from official sources such as [government agencies](https://health.alaska.gov/dph/Epi/id/Pages/Alaskapox.aspx) and are presented in a structured format to enable accurate analysis and detailed understanding of the Alaskapox outbreak situation. The repository is updated regularly to ensure access to up-to-date and reliable information. We hope that these data will be useful in informing public health decisions and in supporting research on the epidemiology and control of infectious diseases.

## Getting the data

### Line list 
CSV: https://raw.githubusercontent.com/fbranda/alaskapox/main/latest.csv  

### Python
```python
import pandas as pd
df = pd.read_csv("https://raw.githubusercontent.com/fbranda/alaskapox/main/latest.csv ")
```
### R
```r
df <- read.csv("https://raw.githubusercontent.com/fbranda/alaskapox/main/latest.csv")
```

## Contributing

If you would like to request changes, [open an issue](https://github.com/fbranda/alaskapox/issues/new) on this repository and we will happily consider your request. If requesting a fix please include steps to reproduce undesirable behaviors.

If you would like to contribute, assign an issue to yourself and/or reach out to a contributor and we will happily help you help us.

If you want to send data to us, you can use our template at [data dictionary](data_dictionary.yml) which makes
it easier for us to add to our list. Just open an issue and attach a CSV / XLSX file in this repository,
or email data to francesco.branda.contact@gmail.com. Remove any Personally Identifiable Information.

## License and attribution

This repository and data exports are published under the CC BY 4.0 license.
