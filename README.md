# GSB 5544 — Lab 4

[Open the rendered report](https://blucat1.github.io/Lab-4-Data-is-Delicious/gsb5544-lab4-completed.html) · [Download the complete package](gsb5544-lab4-completed.zip)

Submit **gsb5544-lab4-completed.html** for the readable report. It contains Part 1 Option B and Part 2 Option B, all Python code and outputs, the source explanations, the API join, the complete shortlist, and a figure. The HTML embeds its styles and figure and opens offline.

If the submission expects a notebook, use **gsb5544-lab4-completed.ipynb**. The ZIP includes both formats plus the source data needed to rerun the work.

## Included files

- `gsb5544-lab4-completed.html`: rendered report.
- `gsb5544-lab4-completed.ipynb`: executed Jupyter notebook.
- `gsb5544-lab4-completed.qmd`: editable Quarto source.
- `Data/lab4/raw/`: retrieved HTML, API JSON responses, and checksum/retrieval metadata.
- `Data/lab4/results/`: webpage, API, and joined CSV files, plus the language summary.
- `Data/lab4/source_metadata.json`: combined retrieval log.
- `requirements-lab4.txt`: Python package versions used.
- `lab-styles.css`: stylesheet used by the report.
- `lab4-review.md`: validation record.
- `gsb5544-lab4-webscraping.html`: original assignment.

## Rerun

Extract the ZIP and preserve the directory structure. Install the Python dependencies in an environment with Jupyter support:

```bash
python -m pip install -r requirements-lab4.txt
```

Open the notebook in Jupyter and run all cells from its directory, or install Quarto and render the source:

```bash
quarto render gsb5544-lab4-completed.qmd --to html
```

On this computer, the existing environment can be selected explicitly:

```bash
QUARTO_PYTHON=/opt/anaconda3/bin/python quarto render gsb5544-lab4-completed.qmd --to html
```

The included cache lets every cell run without network requests or credentials. If a cached response is absent, the visible request code retrieves it and saves its metadata. The recorded results use the supplied snapshot: do not mix refreshed source files with old conclusions. The source HTML reports August 2, 2026; retrieval occurred September 28 UTC (September 27 in California). These dates are intentionally separate in the report.

The API is Gutendex. Available local course files did not show previous use of it; the assignment prohibits APIs already covered in class.
