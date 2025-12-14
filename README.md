## OSS Commercilaization with Hybrid Models

### Description
This repository contains code and data used in the research work of Tanyel Tuncer on open-source software (OSS) commercialization with hybrid business models. 

It applies Non-negative Matrix Factorization (NMF) for topic modelling on a literature corpus and then uses the results to:
- Extract latent topics from publications
- Prepare top words per topic for visualization (e.g. word clouds in Tableau)
- Build business model clusters using NetworkX

The work is associated with the following publication: https://journals.aom.org/doi/abs/10.5465/AMPROC.2025.24079abstract

### Repository Structure – Where to Find What
**📂 Topic Modelling/**

Contains notebooks for:
- Loading and preprocessing the literature corpus
- Building a document–term matrix (e.g., TF-IDF)
- Applying NMF to extract latent topics
- Inspecting topic–word and document–topic matrices

Use this folder if you want to run or adapt the topic modelling pipeline itself.

**📂 Word Cloud Generation/**

Contains code and prepared data for:
- Transforming NMF outputs into a “top words per topic” table
- Exporting the dataset for visualization tools like Tableau
- Generating word clouds that visually represent the topics

Use this folder if you want to visualize topics or reuse the prepared topic–word dataset.

**📂 Business Model Cluster Viz/**

Contains notebooks for:
- Creating network representations of topics or business model elements
- Using NetworkX to cluster and visualize relationships
- Producing the business model cluster diagrams used in the research

Use this folder if you’re interested in network-based clustering and visualization of topic modelling results.
