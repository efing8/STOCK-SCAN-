# STOCK-SCAN-

StockScan is a free, single-page barcode inventory app. Scan a product with your phone camera, enter the quantity on hand, and save. Counts stay in this browser (IndexedDB). There is no account and no subscription.

## Open the app

After GitHub Pages is enabled for the `main` branch from the site root (`/`), open:

https://efing8.github.io/STOCK-SCAN-/

On a phone, open that page and tap **Load starter inventory**. That adds the 11/17 sheet (names, quantities, and Chases or Fillers) into this browser. It skips products you already have, and it does not import prices. You can also add a photo when creating or editing any product.

To try it on this machine, serve the repo root and open `index.html` (camera scanning needs HTTPS or `localhost`; you can also type a barcode).

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080/
