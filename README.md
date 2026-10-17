# kindle-open

Static redirector: `https://hamadalab.github.io/kindle-open/?asin=<ASIN>` forwards to
`kindle://book?action=open&asin=<ASIN>` so that the Kindle app (macOS / iOS) opens the book directly.

Used from Notion, which only renders http(s) links. No data is stored; the ASIN exists only in the clicked URL.
