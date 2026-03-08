# Word Frequency in Moby Dick

A data science project that explores word frequency in Herman Melville's classic novel, Moby Dick, using Python's natural language processing tools.

## Overview

This project scrapes the HTML version of Moby Dick from Project Gutenberg, cleans the text by removing HTML tags and punctuation, and performs a frequency analysis of the words (excluding common English stopwords).

## Analysis Workflow

- **Scrape HTML** using `requests`
- **Extract Text** with `BeautifulSoup`
- **Tokenize** words using `nltk`
- **Clean Data** by removing stopwords
- **Frequency Analysis** to find the most common words

## Files

```
├── notebook.ipynb       # Main analysis notebook
└── mobydick.jpg         # Project banner
```

## Tools

- Python, Requests, BeautifulSoup, NLTK
