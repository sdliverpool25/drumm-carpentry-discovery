# Drumm Carpentry discovery

An editable, public GitHub Pages workspace capturing Digital Drumm’s discovery session with Mary (bookkeeper) at Drumm Carpentry, November 2026.

**Live page:** https://sdliverpool25.github.io/drumm-carpentry-discovery/

The page is a small multi-tab app (hash routing). Tabs: `#notes`, `#whiteboard`, `#stakeholders`, `#tech`, `#usecases`, and `#usecase/N` for a single use case. On a narrow screen the tab bar collapses to a menu.

## What it contains

- **Notes** — key notes on deposits, staged payments, the Schedule Sheet and fixed payments, plus the process maps
- **Whiteboard** — a full-tab Excalidraw canvas (Miro-style) with a true browser fullscreen option, scene export/import and PNG export
- **Stakeholders** — organisation chart (Darren at the top; Mary, Lami, Tony and Ines reporting; Gavin as a dotted external line) and a power/interest grid. Click a person to edit their card; add or delete people and both views update
- **Tech stack** — editable system cards and data-flow rows. A Mermaid diagram is generated from that data for Today and Future state (the custom ERP as the system of record). An advanced box can override the Mermaid source
- **Use cases** — a sortable, filterable list. The creditors report (#9) stays pinned at the top. Monthly reports is use case #8, with the September 2026 checklist on its detail page. Each use case has its own page for process, pain points, ideas, a checklist, image attachments and a whiteboard

Everything on the page is editable. Changes autosave in the current browser only (`localStorage`; images are stored in IndexedDB). They are not written back to GitHub. Use **Export JSON** (images included) or **Download HTML** to keep a copy, and **Import JSON** to load it on another device. Each whiteboard also has its own `.excalidraw` scene export.

## Privacy

This site is public. Customer names, addresses, phone numbers, emails, IBAN/BIC/sort codes, account numbers, VAT/CRO numbers and exact loan amounts are not included. Quote figures are generic examples only. Leave the contact field on a person card blank, and do not attach identifying documents if you plan to share an export.

## Linear

[SHA-96](https://linear.app/shanedrumm/issue/SHA-96/drumm-carpentry-discovery-notes-page-github-pages)
