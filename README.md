# Modular ML Lead Scoring System

A generalized reference implementation for a modular, end-to-end ML system. This project serves as a template for production-grade lead scoring pipelines, developed based on systems I built for multiple B2B organizations.

## Key Features
* **Business-Centric Evaluation:** A framework designed to measure expected revenue/profit value, optimized for scenarios where sales capacity is a fraction of the total lead universe, and we want to rank leads by their expected value add.
* **Modular Architecture:** Separate modules for data preparation, feature engineering, and model selection.
* **Scalable Selection:** A robust process for benchmarking candidate models against the business-specific evaluation framework.
* **Production Pipeline:** Notebook-based training and inference workflow.

## Usage Note
This repository is a **reference implementation**. To use this in a live environment:
1. Provide your own training/inference datasets.
2. Update `data_preparation.py` to reflect your specific schema and labels, and data cleaning/engineering needs.
3. Adjust evaluation cutoffs (and label) in the selection framework to match your sales capacity.
4. Pick a winning model in model selection, update the config in model training, and update the identifiers in model inference.
