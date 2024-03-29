# channels_in_macro

Channels in Macro Papers - How is the word "channel" used in macroeconomic papers?

## Main steps

- Download all papers from top 5 macro journals published in 2015-2021 and collate metadata (identifiers). The journals are: AER, Econometrica, JPE, QJE and RES.
- Identify paragraphs in macro papers that contain the word 'channel'.
- Also, get the number of citations for each paper using Google Scholar. This step is particularly difficult because Google Scholar will force you to do captcha tests every so often and will even block your IP address after you have many "too many queries" in a short period of time. The solution I used is to query Google Scholar using a Tor browser with changing IP addresses and to alert you with a sound whenever a captcha appears (so that you can solve it manually).
- Compile summary statistics.

## Folder directory

- `code`: code for analysis
- `data`: downloaded papers, collated identifiers, filtered paragraphs, and a table indicating whether each paper is a macro paper.  
- `documentation`: memos with documentation of steps + graphs and statistics. Refer to `documentation/Summary of Progress for Channels in Macro 140122.pdf`.
- `output`: a table with the number of citations for each paper. The file is found at `output/macro_papers_citations.csv`.
- `.gitignore`: note that `data` is not saved in GitHub. It is only available in Dropbox.
