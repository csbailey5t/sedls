# Exploratory Text Analysis with Python

Scott Bailey <br/>
Digital Research and Scholarship Librarian <br/>
Copyright and Digital Scholarship Center (CDSC) <br/> 
NC State University Libraries

*Workshop for the Southeast Data Librarian Symposium 2020*

In this interactive workshop, participants will learn to use SpaCy, a natural language processing (NLP) library in Python, to explore text data. Working with single documents and a small corpus, participants will write Python code to identify and visualize named entities, discover and plot terms by frequency, and extract patterns by syntatic constructions. Throughout, we'll approach Python as a tool that can help us gauge the quality of our texts as data, and identify interesting features to explore while refining research questions.  

## Running the workshop code

All of the code in this workshop exists in a Jupyter Notebooks (`.ipynb` files). The workshop code can be run in multiple ways. 

If you already have a local Python installation and are comfortable working with virtual environments, go ahead and create a virtual environment and install the libraries listed in `requirements.txt` in your preferred way. This workshop was developed with Python 3.8 (by way of `pyenv`) and `poetry` for simplicity, but you could use `conda`, `pipenv`, `virtualenv`, or other environment managers. 

If you are just getting started with Python or simply prefer to work in the browser (I recommend this for the live workshop), click on the Google Colab button below to open the workshop notebook in Google Colab, Google's hosted Jupyter Notebook environment. You'll be able to run all of the code in your browser. 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/csbailey5t/sedls/blob/master/exploratory-text-analysis.ipynb)

You can also run the full notebook in Binder. To run in Binder, click the button below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/csbailey5t/sedls/master) 

## Our Corpus: *The Animal Turn*

The digitized collection we'll work with today is from NC State University Libraries' Special Collections: *[The Animal Turn](https://www.lib.ncsu.edu/animal-turn)*. This is a grant-funded collection with substantial materials from NC State University Libraries' Animal Rights and Welfare collections, along with materials from the ASPCA's archives. We'll only be working with a very small subset of texts though. 

This collection is backed by [IIIF (International Image Interoperability Framework)](https://iiif.io/) and includes OCR text. With permission, I've taken advantage of the public IIIF manifest for the collection, and scraped the OCR text. 