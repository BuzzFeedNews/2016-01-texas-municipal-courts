# Analysis of Texas Court Data

This repository contains data and analysis regarding criminal cases in Texas municipal courts. The findings are referenced in the BuzzFeed News article, "[The Ticket Machine](http://buzzfeed.com/alexcampbell/the-ticket-machine)", published January 26, 2016.

## Data 

The analysis depends on data collected and published by the Texas Office of Court Administration, for fiscal years 2013-2015. This analysis uses two fields in particular: 1) the number of criminal cases disposed, and 2) the number of cases where fines were satisfied by jail time. 

The raw data can be downloaded [here](http://card.txcourts.gov/ReportSelection.aspx).

## Analysis

This repository's [`texas_municipal_court.ipynb` notebook](notebooks/tx-municipal-court-analysis.ipynb) reformats the raw data, and then ranks municipal courts by the percent of total criminal cases disposed where fines were satisfied by jail time. The results support the following finding:

- "In fact, traffic and other fine-only offenses result in jail at a higher rate in Port Arthur than most other cities in the state, according to a BuzzFeed News analysis of Texas court data."

Since not all courts reported or accurately reported their data, it's not possible to provide a definitive ranking of all cities, but the analysis shows that Port Arthur ranks among the highest given the available data.

To re-run the analysis yourself, you'll need to install the libraries listed in [`requirements.txt`](requirements.txt) and open the [`texas_municipal_court.ipynb` notebook](notebooks/tx-municipal-court-analysis.ipynb) in [Jupyter/IPython](http://jupyter.org/).


## Questions / Feedback?

Email the author at kendall.taggart@buzzfeed.com.
