# Sañcaya

A collection of searchable Indic texts and research-paper transcriptions,
assembled for reading and corpus search. Texts include Devanagari and Latin
transliteration; transcription, OCR quality, and reference conventions vary.

## Organisation

- Subject folders such as `Jyotisham`, `Puranani`, `Vedic texts`, and
  `Kavyas, Kavya shastra` contain classical texts and transcriptions.
- `gretil/` contains texts with GRETIL source and edition information in
  their headers.
- `Bauddha/` includes Buddhist texts and a `Tipitaka/` collection.
- `patra-darpan/papers/` contains research-paper Markdown exported from
  [Patra Darpaṇa](https://github.com/suchakr/patra-darpan).
  `patra-darpan/catalog/corpus-manifest.jsonl` records the exported papers
  and their source references.

## Documented sources

The following attributions can be verified in this checkout. They are
examples, not a complete provenance map for every file.

| Source | Evidence in this repository |
| --- | --- |
| Göttingen Register of Electronic Texts in Indian Languages (GRETIL) | [Brahmāṇḍapurāṇa](gretil/sa_brahmANDapurANa.txt) includes the upstream XML URL, edition, contributors, and licence in its header. |
| Sanskrit Wikisource | [Taittirīya Saṃhitā](Vedic%20texts/YV/TS%20viswara.txt) names its [Wikisource source](https://sa.wikisource.org/s/a7r). |
| Digital Corpus of Sanskrit (DCS) | The [Ṛtusaṃhāra addition](https://github.com/cahcblr/sanchaya/commit/63a29a3) records that its text was obtained from DCS. |
| Research-paper publishers and mirrors, through Patra Darpaṇa | Exported paper headers and the [paper manifest](patra-darpan/catalog/corpus-manifest.jsonl) retain source references. |

Other files may carry source notes in their headers. Where provenance is
missing, do not infer an edition, contributor, or licence from the folder name.

## Search and retrieval

[Sanchaya-Zoekt](https://github.com/suchakr/sanchaya-zoekt) provides lexical
search over this repository. Patra Darpaṇa builds passage, vector, and entity
projections for a selected release scope. Inclusion here does not imply that
all retrieval layers cover every file.

## Rights

Texts, transcriptions, and papers retain the rights and licence conditions
of their respective sources. This repository does not grant a blanket licence
for the corpus. Consult each file's source and licence notes before reuse;
missing notes do not establish permission.
