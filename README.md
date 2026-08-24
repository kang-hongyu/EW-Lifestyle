# Evidence-Weighted Lifestyle Knowledge Reasoning Resources

This repository provides supplementary resources for the study:

**“An Evidence-Weighted Knowledge Reasoning Framework for Personalized Lifestyle Decision Support in Chronic Disease.”**

The repository contains the evaluation dataset and prompt templates used in the knowledge extraction and verification processes for constructing the evidence-weighted lifestyle knowledge graph (EW-LKG).

---

## Contents

The repository includes the following resources:

* **QA dataset**: Benchmark question–answer pairs (621).
* **Schema definition**: Structured lifestyle knowledge schema with entity and relation types.  
* **Extraction prompt**: Prompt template for schema-constrained triple extraction.  
* **Verification prompt**: Prompt template for triple validation and consistency checking.  
* **Triple Annotations**: Gold-standard triple annotations from 200 manually annotated abstracts.
* **Adversarial queries**: Adversarial safety evaluation query set.  
* **Benchmark QA**: 521-question held-out test subset with reference answers and correctness labels across models.  
* **Verifier annotations**: Knowledge Graph Verifier annotations and correction outcomes.  
* **EW-LKG**: Evidence-Weighted Lifestyle Knowledge Graph. 
---

## Repository Structure

```
/qa_dataset
    Lifestyle-QA dataset.xlsx
    Lifestyle-QA dataset_test_labeled_20methods.xlsx
/schema
    Lifestyle schema.xlsx

/prompts
    Extraction prompt.docx
    Verify prompt.doc

/kg_data
    kg_label_set.xlsx
    kg_200.graphml

/Verifier_annotations
    reflection_correction.xlsx

/Adversarial_queries
    safety_test_set_all.xlsx
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
