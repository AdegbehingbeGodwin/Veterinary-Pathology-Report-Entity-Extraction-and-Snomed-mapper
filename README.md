## Introduction

This project explores the potential of AI technologies, specifically NLP and ML, to extract and classify entities from veterinary pathology reports. The objective is to evaluate the performance of state-of-the-art models, organize extracted information, and map results to clinical standards like SNOMED and ICD-10. This work aligns with efforts to automate veterinary diagnostics and improve data processing efficiency.

## Methodology

### Data Sourcing

The dataset comprises veterinary pathology reports sourced from publicly available documents,historical reports from the Australian Society for Veterinary Pathology.

### Process Overview

1. **Model Utilization**: The project employed LLaMA 3 for entity extraction, leveraging its advanced capabilities in understanding and parsing unstructured text.
2. **Groq API**: The Groq platform was used to execute the model efficiently, facilitating rapid extraction and classification.
3. **Entity Organization**: Extracted information was categorized into:
   - **Animal Species**
   - **Symptoms**
   - **Necropsy Findings**
   - **Diagnoses**
   - **Etiological Agents**
4. **SNOMED Mapping**: Preliminary mapping to SNOMED terms was performed, with plans for full automation.

## Results

- **Entity Extraction**: The process successfully identified key entities, demonstrating the model’s effectiveness.
- **Categorization**: Extracted entities were systematically organized for better interpretability.
- **SNOMED Mapping**: While initial mappings were successful, gaps in veterinary-specific terminology were noted, highlighting areas for refinement.

## Next Steps

- **API Integration**: Automate the mapping process by connecting directly to the SNOMED API for real-time lookups.
- **Model Improvement**: Fine-tune and evaluate LLaMA 3’s performance on larger and more diverse veterinary datasets.
- **Scalability**: Expand the pipeline to handle bulk processing of veterinary pathology reports.

## Conclusion

This project demonstrates the feasibility of leveraging AI for veterinary pathology diagnostics. The initial results are promising and pave the way for further research into automating and enhancing clinical data processing.
