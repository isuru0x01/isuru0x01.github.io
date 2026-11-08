---
title: Releasing a 10-Million-Row Sinhala Narrative Corpus for Low-Resource NLP
date: 2026-02-15 14:00:00 +0530
categories: [Research, Natural Language Processing]
tags: [sinhala-nlp, datasets, zenodo, open-science]
---

We are excited to announce the public release of a **10-million-row Sinhala narrative corpus** alongside the **Sinhala Stories Dataset Creator (v1.0)**, openly accessible on Zenodo.

South Asian languages—and Sinhala in particular—frequently encounter a substantial "data divide" in computational linguistics. The shortage of large-scale, ethically curated, and structurally clean textual corpora has historically constrained the pre-training and fine-tuning of modern natural language processing models.

### Key Outputs

- **Narrative Corpus**: [DOI: 10.5281/zenodo.21194859](https://doi.org/10.5281/zenodo.21194859)  
  *Samarappulige, I., & Ekanayake, K. (2026). A 10-million-row Sinhala narrative corpus for low-resource NLP: Dataset construction, statistical characterisation, and ethical considerations.*
- **Dataset Creator Software**: [DOI: 10.5281/zenodo.21195380](https://doi.org/10.5281/zenodo.21195380)  
  *Samarappulige, I. (2026). Sinhala Stories Dataset Creator (Version 1.0).*

### Methodology & Ethical Considerations

The dataset creation pipeline features:
- **Encoding Normalization**: Resolving Unicode character inconsistencies and variant diacritic encodings common in Sinhala digital text.
- **De-duplication & Quality Filtering**: High-precision n-gram and min-hash deduplication algorithms to eliminate spam and boilerplate text.
- **Ethical Anonymization**: Heuristic and rule-based masking of personally identifiable information (PII).

We look forward to seeing how the community uses this corpus for downstream tasks including text classification, language modeling, sentiment analysis, and machine translation.

