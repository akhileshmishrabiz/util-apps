# Invoice Generator

LivingDevOps GST tax invoice generator for bootcamp students. A single static page: fill in the form, check the live A4 preview, download the PDF.

- GST inclusive or exclusive fees, split into CGST + SGST (same state) or IGST (other states)
- Zero-rated export invoices under LUT for fees in USD, EUR or GBP
- Amount in words, SAC code, digitally signed block
- "New invoice" moves to the next invoice number; "Save to list" keeps invoices in this browser's local storage

## Deploy on Vercel

1. Vercel → Add New → Project → import `akhileshmishrabiz/util-apps`.
2. Set **Root Directory** to `invoice-generator`.
3. Framework preset: **Other**. Leave build and output settings empty.
4. Deploy. Every push to `main` that touches this folder redeploys it.

## Run locally

```
npx serve invoice-generator
```
