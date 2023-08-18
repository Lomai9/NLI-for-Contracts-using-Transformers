# NLI-for-Contracts-using-Transformers

## Natural Language Inference on ContractNLI Dataset
This project aims to perform natural language inference (NLI) on the ContractNLI dataset. The ContractNLI dataset is designed for document-level NLI on contracts to automate and support the contract review process. The goal is to classify whether a hypothesis logically follows from the contract and identify evidence spans that support the decision.

## Background
The ContractNLI dataset is a collection of contracts annotated with hypotheses and their corresponding classifications. The dataset consists of document texts, spans, annotations, and labels. The task involves NLI, which determines the logical relationship (entailment, contradiction, or not mentioned) between a hypothesis and a contract.

![download](https://github.com/Lomai9/NLI-for-Contracts-using-Transformers/assets/77353623/38084391-7639-4842-bf29-4b3633d9a166)

## Assignment Tasks
### Q1: Dataset Preparation
The first task is to analyze the statistics and structure of the ContractNLI dataset. This step involves understanding the dataset's composition, considering its size, and evaluating any class imbalances. Based on the analysis, a strategy should be devised to generate new files for training, validation, and testing. The approach should be summarized in a textual cell in the Jupyter Notebook.

### Q2: NLI using Transformer-Based Approaches
Two transformer-based approaches will be used for NLI on the ContractNLI dataset. State-of-the-art (SOTA) approaches, such as those available on platforms like Papers with Code, will be explored. Hugging Face's Transformers library will be used to check if pre-trained models, such as DeBERTa, are available. The selected models will be fine-tuned on the training dataset from ContractNLI. The performance of the two models will be reported.

### Q3: Performance Analysis and Error Analysis
The performance of the two models will be analyzed and compared. A methodology will be designed to perform error analysis, aiming to understand the potential reasons behind the model's errors. The analysis should be documented in a textual cell in the Jupyter Notebook.

### Q4: Proposal for Improvement
Based on the findings from Q3 and external readings, two ideas will be proposed to improve the approaches used in Q2. These ideas should focus on directly fine-tuning pre-trained models to enhance performance. The proposals should be explained in a textual cell in the Jupyter Notebook.


Resources
ContractNLI dataset: https://stanfordnlp.github.io/contract-nli/
Hugging Face's Transformers library: https://huggingface.co/transformers/

