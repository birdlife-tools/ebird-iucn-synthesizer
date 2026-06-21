# eBird-IUCN Synthesizer

CLI tool and Python library that synthesizes eBird sighting data with IUCN Red List threat categories.

## Problem

Ecologists spend days manually synthesizing data when preparing feasibility studies and reports. They must manually compare raw bird sighting data (eBird) with threat categories (IUCN Red List). These two databases don't communicate automatically.

## Solution

Pull data from eBird API for a specified region, map taxonomy to IUCN database, and generate clean JSON/CSV reports.

## Technical Stack

- eBird API (`v2/data/obs/...`)
- IUCN Red List API
- Taxonomic synonymy resolution via fuzzy matching
- Export in QGIS-ready format

## Status

🚧 Planning

## License

MIT — see [LICENSE](LICENSE)
