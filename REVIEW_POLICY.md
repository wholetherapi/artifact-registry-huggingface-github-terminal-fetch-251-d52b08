# Artifact Registry Review Policy

## License adjudication for derived artifacts

1. The effective license of a derived artifact is the license of its **direct
   content source** - the upstream data collection that the artifact was
   adopted from.
2. Processing tools are **not** content sources. A generator model, tokenizer,
   cleaner or synthesizer license governs use of that tool, not the data it
   produced. Before treating a generator as a licensing candidate, read its
   full license text and check whether it claims any rights in its outputs or
   excludes data from its grant.
3. If several content sources apply, choose the most permissive license for
   derivative and secondary use among the applicable content sources only.
4. Record the chosen license identifier exactly as its source declares it, the
   entry it was inherited from, and a one-line justification citing the
   decisive clause in the license documents.
