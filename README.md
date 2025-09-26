# Keyword Extraction from BibTeX References

This project provides a Jupyter Notebook for extracting and analyzing keywords from academic references stored in BibTeX (.bib) files. It is designed to help researchers and students organize, clean, and validate reference keys and titles for thesis or research projects.

## Features
- Loads BibTeX files using `bibtexparser`
- Cleans and normalizes reference titles
- Extracts keywords from titles and author names
- Validates BibTeX entry keys for consistency
- Provides step-by-step code cells for exploration and debugging

## Files
- `keyword_extraction.ipynb`: Main notebook for keyword extraction and analysis
- `ref.bib`: Sample BibTeX file containing references
- `export.bib`: (Optional) Additional BibTeX file

## Requirements
- Python 3.x
- Jupyter Notebook
- `bibtexparser` library

## Installation
1. Install Python and Jupyter Notebook if not already installed.
2. Install required Python package:
   ```powershell
   pip install bibtexparser
   ```
3. Open `keyword_extraction.ipynb` in Jupyter Notebook or VS Code.

## Usage
1. Place your BibTeX file (e.g., `ref.bib`) in the project directory.
2. Open and run the notebook step by step.
3. Review the output for cleaned titles, extracted keywords, and key validation.

## Customization
- Edit the `STOPWORDS` list in the notebook to adjust which words are removed from titles.
- Modify code cells to suit your specific BibTeX structure or analysis needs.

## License
This project is provided for academic and research purposes. Feel free to modify and use as needed.
