# Internal Artifact Registry

This repository is the internal registry for datasets and models produced or
consumed by the AI platform team. Every entry has:

- `README.md`  - human readable card (provenance, composition, usage notes)
- `metadata.json` - machine readable record (ids, schema, license, relations)

License documents that are not part of a well-known SPDX family are stored next
to the entry (for example `LICENSE-MODEL`).

## Layout

- `datasets/` - dataset collections and derived datasets
- `models/` - generator and utility models
- `REVIEW_POLICY.md` - how the data-governance team adjudicates licenses
