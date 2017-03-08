# Robinhood-1099-B-Transactions-Export-Tool

* Extract transactions from Robinhood Consolidated 1099 PDF

* Processes:
1. Use <a href="https://mozilla.github.io/pdf.js/">pdf.js</a> to extract pages one by one from PDF
2. Convert each page into a canvas element
3. Use <a href="http://antimatter15.com/ocrad.js/demo.html">Ocrad.js</a> to scan each page image into texts
4. Exact transaction information from texts
5. Display & Export to CSV
