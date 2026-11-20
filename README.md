# Almost Equal

Finds near-duplicate names within one spreadsheet list, on your own computer. The page makes no network requests.

- **Download:** [latest release](../../releases/latest) (one file, `almost-equal.html`)
- **Page:** https://Kavin665.github.io/almost-equal/
- **Guide:** [Power Query fuzzy merge on Mac Excel: what is reported missing, and what to do instead](https://Kavin665.github.io/almost-equal/fuzzy-merge-missing-on-mac-excel.html)

## Limit

Free. Uses the first **1,000 rows** of the file you load. That means at most 1,000 distinct values and at most 499,500 comparisons per run.

## What it does

Finds near-duplicate rows inside one list. Load a .xlsx or .csv file (.xlsm, .xls, .tsv and .ods are accepted by the page but untested), pick the column, review each proposed pair with its score, click Apply decisions, then download the cleaned list and a log of removed rows as CSV or XLSX. Nothing is removed until you apply. It does not merge files.

## What is and is not confirmed

- Confirmed: the page made no network requests through a full run (load, match, review, apply, CSV and XLSX export), recorded in a browser's network panel.
- Not confirmed: running it with the network adapter switched off, and opening it by double-click from disk. Try the built-in sample data first.
- Not tested: Safari, Firefox, or any Mac. Also untested: loading .xlsm, .xls, .tsv and .ods files. Nobody has tried them yet.

## Pricing

There is no paid version and no price. If you need two-list matching or more than 1,000 rows, open an issue and say what you were trying to do.

## Support

Open an [issue](https://github.com/Kavin665/almost-equal/issues). Please do not paste real customer data into an issue.

*Microsoft, Excel and Power Query are trademarks of their owners. This product is not affiliated with or endorsed by Microsoft.*

## Licence

The tool includes SheetJS Community Edition v0.20.3, copyright SheetJS LLC, under the Apache License 2.0. The notice is in the tool's About panel.
