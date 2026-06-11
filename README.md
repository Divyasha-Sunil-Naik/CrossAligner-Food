# CrossAligner-Food

**A Gold Standard Benchmark for Multi-Perspective Food Ontology Alignment**

CrossAligner-Food is an expert-curated gold standard benchmark for ontology alignment in the food domain. The benchmark consists of three complementary food-related ontologies and focuses on identifying meaningful semantic bridges across heterogeneous perspectives of the same domain.

Existing benchmark tracks primarily focus on equivalence and subsumption relations between ontologies with overlapping domains and similar modeling objectives. In contrast, the CrossAligner-Food dataset support the study of how different ontology perspectives can be related while preserving their conceptual distinctions.
This makes the dataset useful for studying alignments where related concepts can be linked without being forced into a single meaning.


## Overview
The benchmark is constructed from three existing ontologies representing complementary perspectives of the food domain from BioPortal.

Table 1. Summarizes the perspectives represented by the selected ontologies.

| Ontology | Perspective | Example Concepts |
|----------|-------------|------------------|
| **ONS** | Food material and diet | vegan diet, plant food product |
| **OccO** | Food-service occupations | chef or head cook, waiter, bartender |
| **MeSH** | Food quality and public health | food contamination, food labeling |




Ontology subsets were extracted from the selected ontologies using ROBOT (http://robot.obolibrary.org/). 

Table 2. Statistics summary of the extracted ontology subsets.

| Ontology Subset | Classes | Object Properties | Data Properties | Definitions | Restrictions |
| --------------- | ------- | ----------------- | --------------- | ----------- | ------------ |
| ONS             | 26      | 4                 | 0               | 26          | 12           |
| OccO            | 52      | 12                | 1               | 45          | 71           |
| MeSH            | 13      | 0                 | 0               | 13          | 0            |


---

## Workflow Overview

![CrossAligner-Food Workflow](figures/Workflow.png)

**Figure 1.** Workflow used to construct the CrossAligner-Food benchmark.

---





