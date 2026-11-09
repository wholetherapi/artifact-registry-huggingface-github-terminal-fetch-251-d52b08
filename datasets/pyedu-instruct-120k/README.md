# pyedu-instruct-120k

Instruction-tuning dataset for Python education assistants.

- **Derived from:** `pyedu-corpus` (Python-Edu subset). This dataset was adopted
  from that upstream collection.
- **Response synthesis:** assistant responses were synthesized using the
  generator model `cortex-coder-32b-instruct`.
- **Schema:** `instruction` (string), `response` (string), `topic` (string),
  `difficulty` (string)
- **Rows:** 120,000
- **License:** pending review (see `metadata.json`)

## Notes

The upstream collection and the generator model both carry license information
that is relevant to a release review. The generator is distributed under the
Cortex Community License v1.2; the full text is kept in the model entry in this
registry.
