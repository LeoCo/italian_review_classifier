# Italian NLP Classifier

Development of a NLP Multiclass Classifier trained from Italian Amazon.it reviews.

## Getting Started

This repository contains some iPython Notebooks, datasets and documents. I recommend to read the documents first and then run the python code.

### Prerequisites

You need to install scrapy, scikit-learn and their dependecies to run the python code.
```
import sklearn
import scrapy
```

## Built With

* [Scrapy](https://scrapy.org) - The Scraping library
* [Scikit-learn](http://scikit-learn.org/stable/) - The Machine Learning Library

## Files in the repository

* Report.pdf - The core document of the project
* Proposal.pdf - The document containing the origin of the work
* data_analysis.ipynb - Data analysis and preprocessing
* sentiment_analysis.ipynb - Model training and Testing
* sentiment_analysis_2classes.ipynb - Model training and Testing of 2-label classifier
* reviews.jl - JSON line Italian dataset
* reviews_eng.jl - JSON line English dataset
* reviews_eng_big.jl - JSON line English big dataset
* scraper.zip - Scrapy project to scrape Amazon.it
