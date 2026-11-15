# Hospital Waiting Times in England

An interactive dashboard comparing NHS hospital waiting times across England's 36 Integrated Care Boards (ICBs), January to September 2026.

**Live dashboard:** https://YOUR-USERNAME.github.io/YOUR-REPO/  *(replace after you switch on GitHub Pages)*

## What it shows
- Share of people waiting less than 18 weeks, against the 92% NHS Constitution standard
- People waiting **per 100,000 residents**, so large and small areas compare fairly
- A choropleth **map** of all 36 ICBs, with a ranked bar chart alongside
- Trend for any area and type of care, and England's series from 2019

## Data sources
| Data | Source |
|---|---|
| Waiting times | NHS England, Consultant-led Referral to Treatment (RTT) waiting times, monthly full extracts Jan–Sep 2026 and England time series |
| Population | ONS, Population density for LSOAs in England and Wales, mid-2022 to mid-2024 (published 7 Nov 2025), mid-2024 column |
| Lookup | ONS, LSOA (2021) to SICBL, ICB, NHSER and LAD (April 2026) |
| Boundaries | ONS, Integrated Care Boards (April 2026) Boundaries EN BSC |

## Method notes
- Population is summed from 33,755 LSOAs to ICBs (England total 58,620,101, mid-2024).
- Rate per 100,000 = waiting pathways ÷ ICB population × 100,000. It counts pathways, not people, and uses 2024 population against 2026 waits, so treat it as approximate.
- Percentages for a type of care are hidden where fewer than 100 people are waiting.
- A warning is shown where an area's total changes by more than 15% in a month (possible missing or moved trust data).
- Map boundaries are simplified for web display.

## Licences
Code: MIT (see `LICENSE`). Data: contains public sector information licensed under the [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/). Source: Office for National Statistics licensed under the Open Government Licence v3.0. Contains OS data © Crown copyright and database right 2026.

This is an independent project and is not produced or endorsed by NHS England, the NHS or ONS.
