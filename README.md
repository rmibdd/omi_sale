# Oriental Merchants, Inc. — Special Price List

Live page: `https://rmibdd.github.io/omi_sale/`

## Update prices
1. In Excel, keep these column headers (row 1):
   `item_code, brand, name, price, offer, expiry, category, barcode`
   - `offer`: `B1T1` or `Discounted`
   - `expiry`: `Near expiry` or blank
   - `barcode`: optional EAN/UPC from the pack (lets the scanner match barcodes)
2. File › Save As › **CSV UTF-8** and name it `pricelist.csv`.
3. On GitHub: open the repo › **Add file › Upload files** › drop the new `pricelist.csv` › Commit.
4. The page updates in ~1 minute (refresh to see it).

## Files
- `index.html` — the dashboard (Overview, Catalog, QR/barcode scanner)
- `pricelist.csv` — the product data the page reads
