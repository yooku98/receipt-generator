# YookuData Receipt Generator

A browser-based tool for producing clean, printable service receipts — fill in the client and line items, then print or save as PDF.

**Live demo:** https://yooku98.github.io/receipt-generator/

## Features

- Client details: name/company, optional email and phone
- Line items (service, quantity, unit price) with an "Add Service" button and automatic totals
- Currency selection, payment method and payment status
- Print / save to PDF via the browser's print dialog
- Web app manifest so it can be installed to a phone's home screen

## Stack

A single `index.html` with inline CSS and vanilla JavaScript (IBM Plex fonts). No build step, no backend — nothing leaves the browser.

## Run locally

```bash
python3 -m http.server 8000
```

## Deployment

Served by GitHub Pages from the root of `main`.
