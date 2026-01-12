# Modular ML Lead Scoring System

A generalized reference implementation for a modular, end-to-end ML system. This project serves as a template for production-grade lead scoring pipelines, developed based on systems built for multiple B2B organizations.

## Key Features
* **Business-Centric Evaluation:** A framework designed to measure expected revenue/profit value, optimized for scenarios where sales capacity is a fraction of the total lead universe.
* **Modular Architecture:** Separate modules for data preparation, feature engineering, and model selection to prevent training-serving skew.
* **Scalable Selection:** A robust process for benchmarking candidate models against business-specific KPIs.
* **Production Pipeline:** Notebook-based training and inference workflow designed for rapid deployment and iteration.

## Usage Note
This repository is a **reference implementation**. To use this in a live environment:
1. Provide your own training/inference datasets.
2. Update `data_preparation.py` to reflect your specific schema and labels.
3. Adjust evaluation cutoffs in the selection framework to match your sales capacity.
4. Replace placeholder features with domain-specific signals.
