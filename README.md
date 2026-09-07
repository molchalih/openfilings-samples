# OpenFilings sample data

Free 20-row samples of two data files built from public-domain US federal filings, snapshot **2026-09-07**. Download them straight from `samples/` — no account, no email, no checkout.

| File | Rows | Columns | What it is |
|---|---|---|---|
| [`samples/expiring_541512_sample.csv`](samples/expiring_541512_sample.csv) | header + 20 | 30 | Federal prime contracts and orders under NAICS 541512 whose period of performance ends in the next 12 months. Incumbent, agency, contracting office, values, dates, set-aside, place of performance, `how_to_compete`, link to the official award page |
| [`samples/funders_VT_sample.csv`](samples/funders_VT_sample.csv) | header + 20 | 33 | Vermont private foundations that filed a 990-PF electronically. Assets, revenue, contributions received, grants paid, phone, website, the Part XV application procedure as filed, preselected-only flag |
| [`samples/grants_VT_sample.csv`](samples/grants_VT_sample.csv) | header + 20 | 13 | Grants paid by those foundations: recipient, city, state, purpose, amount |

## Sources

- Expiring contracts: the monthly award archive published by the federal spending site, archive 2026-08-06. Terms permit copying, adapting and redistributing the data.
- Foundations: the federal 990-PF e-file XML archives for the twelve months to the snapshot date.
- No federal agency produced, reviewed, approved or endorses these files, and no agency trademark, logo or seal is used.

## Licence

Samples: public-domain source data, redistributable. Reuse them freely, with or without attribution.

## Full files

These samples are the free preview of files I sell: one zip per six-digit industry code (262 listed) and one per state (51 listed), each with CSVs, a spreadsheet, a README and a licence. One-time purchase, no subscription, no login — https://payhip.com/OpenFilings. The full NAICS 541512 file holds 6,040 rows; the full Vermont file holds 314 funders, 4,412 grants and 1,356 officers.
