# RIPPL 🌊 — Climate futures, connected

A fully working, browser-based **Nordic Climate Risk & Adaptation Research Studio** concept. Built as an independent portfolio demonstration relevant to the research activities described in CRISP Insight AB's Junior Researcher vacancy.

## Run it

**Easiest:** unzip the folder and double-click `index.html`. No installation, account, API key, database or internet connection is required for the app itself. The optional Google Fonts and external research links use the internet; the app falls back to system fonts offline.

**Optional local web server:** from this folder run `python -m http.server 8000` and open `http://localhost:8000`.

## Features

1. Mission Control: selectable climate hazards, SSP narratives, time horizons and risk pathway map.
2. Risk Cascade: interactive conceptual cross-sector cascading risk pathway.
3. Future Lab: three socioeconomic futures and three adaptation candidates with explicit trade-offs.
4. Evidence Vault: searchable, filterable, clickable bibliography of official and peer-reviewed starting sources.
5. Workshop Room: add and remove stakeholder observations, locally saved in browser storage.
6. Research Brief: preview, download, copy and print a synthesis containing the selected case and stakeholder notes.
7. Responsive layout for desktop, tablet and mobile.

## Research integrity

**This is a concept demonstrator, not a scientific climate risk assessment.** It uses qualitative illustrative narratives and conceptual risk pathways. It does not ingest live climate datasets, simulate climate outcomes, estimate impacts, calculate probabilities, or establish causal links. Source records are research starting points; verify each source before formal use. No affiliation with or endorsement by CRISP Insight or Dr Simona Pedde is claimed.

## Data privacy

Workshop observations and selections are saved only in the browser's localStorage. Do not enter confidential or personally identifying information. Reset clears the stored app state in this browser.

## Project structure

- `index.html` — application shell
- `style.css` — visual design and responsive layout
- `script.js` — application data, interactions, exports and state

## Suggested next research iteration

Validate one specific Stockholm climate hazard and cascading pathway using SMHI datasets, relevant municipal and county documents, and peer-reviewed studies. Create an evidence table for each hypothesized link, document confidence and uncertainty, and conduct stakeholder validation before drawing conclusions.
