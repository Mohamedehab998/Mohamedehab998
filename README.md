# Open source work

I maintain small tools for Arabic text, localization, and PDF extraction. The projects below use reproducible examples and tests so other developers can verify the results.

| Project | What it does |
| --- | --- |
| [Arabic PDF Test Kit](https://github.com/Mohamedehab998/arabic-pdf-test-kit) | Tests Arabic PDF extraction with six cases covering digits, punctuation, and mixed Arabic and English. |
| [Catalog Placeholder Check](https://github.com/Mohamedehab998/catalog-placeholder-check) | Checks that translations keep the named placeholders their applications expect. |
| [Bidi Text Audit](https://github.com/Mohamedehab998/bidi-text-audit) | Reports invisible Unicode direction controls that can affect how mixed-language text displays. |

## Upstream work

[pdfplumber #1442](https://github.com/jsvine/pdfplumber/pull/1442) proposes speeding up text extraction from tall tables while preserving PDF text order. On a synthetic table with 750 rows, extraction took 13.57 seconds before the change and 0.27 seconds after it. The pull request includes the benchmark and tests for row boundaries and empty rows.
