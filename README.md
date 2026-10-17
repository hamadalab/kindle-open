# kindle-open

Static redirector used from Notion (which only renders http(s) links):
`https://hamadalab.github.io/kindle-open/?asin=<ASIN>`

- iPhone / iPad → `kindle://book?action=open&asin=<ASIN>` (Kindle app)
- Mac → `https://read.amazon.co.jp/?asin=<ASIN>` (Kindle Cloud Reader). Kindle for Mac 7.x (Catalyst) no longer
  opens a book from `kindle://` or universal links; it only launches the app (confirmed 2026-10-18, v7.69).
- Other / `manual=1` → buttons only (Cloud Reader / Kindle app / Amazon product page).

No data is stored; the ASIN exists only in the clicked URL.
