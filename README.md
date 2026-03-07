# Evidence-Weighted Lifestyle Knowledge Reasoning Resources

This repository provides supplementary resources for the study:

**“An Evidence-Weighted Knowledge Reasoning Framework for Personalized Lifestyle Decision Support in Chronic Disease.”**

The repository contains the evaluation dataset and prompt templates used in the knowledge extraction and verification processes for constructing the evidence-weighted lifestyle knowledge graph (EW-LKG).

---

## Contents

The repository includes the following resources:

* **QA Dataset**
  A curated set of lifestyle-related question–answer pairs used to evaluate reasoning performance across different retrieval settings.

* **Schema Definition**
  The structured schema used for lifestyle knowledge representation, including entity types and relation types.

* **Extraction Prompt**
  The prompt template used to guide large language models in extracting schema-constrained triples from biomedical literature.

* **Verification Prompt**
  The prompt template used for validating extracted triples and ensuring schema consistency and evidence alignment.

---

## Repository Structure

```
/qa_dataset
    Lifestyle-QA dataset.xlsx

/schema
    Lifestyle schema.xlsx

/prompts
    Extraction prompt.docx
    Verify prompt.doc
```

---

## Usage

These resources can be used to:

* reproduce the knowledge extraction pipeline
* evaluate knowledge-based reasoning for lifestyle-related queries
* develop or benchmark knowledge graph–augmented LLM systems in health informatics

---

## License

This repository is released for academic research use.
