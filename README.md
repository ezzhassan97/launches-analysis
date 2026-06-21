# Nawy · Launches & Releases Analysis

Interactive dashboard analysing real-estate project launches detected and structured
from Nawy ⇄ developer WhatsApp groups.

## Features
- Filter by **developer**, **level** (Main Compound vs Phase), **area**, and **date range**
- Toggle to exclude duplicates / already-created records
- KPI cards, per-developer & per-area stacked charts, activity timeline, donut split
- Sortable, searchable, paginated detail table
- Fully self-contained single HTML file (data embedded, no backend)

> **Note:** the commercial **Type** dimension (Launch / EOI vs Release / inventory)
> is not yet present in the source export and its filter is disabled pending an
> extra `category` field from the WhatsApp automation.

## Run
Open `index.html` in any browser. Deployed at https://launches-analysis.vercel.app
