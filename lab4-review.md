# Lab 4 validation record

- Part 1 Option B: BeautifulSoup parses the daily ebook HTML list into a 10-row, 6-column pandas DataFrame. No use of `pd.read_html`.
- Part 2 Option B: 10 successful individual Gutendex API responses form a 10-row, 6-column pandas DataFrame.
- Both parts explain the data, purpose, observational units, main variables, and linked sources.
- The join is a left merge on Gutenberg book ID with one-to-one validation: 10 unique rows, 11 columns, 10 matches, no unmatched IDs.
- The complete selected ranking, result summaries, figure, and exported data are included.
- Ranking snapshot: August 2, 2026. Retrieval occurred September 28 UTC / September 27 in California. The report explicitly distinguishes these dates.
- Daily downloads total 53,207 across the selected 10 books. Moby Dick leads with 7,134. All 10 API entries list English and EPUB availability; no author metadata is missing.
- All 11 included source responses have HTTP 200 metadata and verified SHA-256 checksums.
- Quarto rendered successfully; the notebook contains eight executed code cells and zero error outputs.
- The extracted submission ZIP was rerun in a fresh kernel with requests blocked. All eight original code cells completed and reproduced the joined CSV exactly.
- HTML image, script, and stylesheet resources are embedded. The report opening and embedded chart were visually inspected.
- Available local course materials did not show prior Gutendex usage. Complete classroom API history could not be established from those files.

The ZIP contains only the source responses used in the submitted analysis; exploratory API probes are excluded.
