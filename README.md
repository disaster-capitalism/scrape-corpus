# Scrape the Corpus "Studies on Water"
This repository contains the code for scraping the text of the corpus "Studies on Water" issued by the OECD from PDF files as part of the "Markets for Resilience or Disaster Capitalism" project. This is done in the notebook `scrape_studies_on_water_pdf.ipynb`. Please note that to run the notebook the pdf documents of the corpus (which can be purchased from the OECD [website](https://doi.org/10.1787/22245081)) need to be stored in a `pdfs/` folder. The text is stored in JSON format for further processing. Further requirements are the PyMuPDF Python Package (version: 1.19.6), which can be installed using `pip`:

```console
pip install pymupdf==1.19.6
```

PyMuPDF requires Python 3.7 or later.

## References
OECD (2022). OECD Studies on Water. <https://doi.org/10.1787/22245081>
