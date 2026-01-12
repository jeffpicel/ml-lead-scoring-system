# ml-lead-scoring-system
Generalized reference implementation for a modular end-to-end ML system for lead scoring, featuring:
- business relevant evaluation framework
- modular data prep and feature engineering
- a highly scalable model selection process
- production-ready notebook-based training/inference pipeline.

I developed this reference code as a template after building multiple ML lead scoring systems across multiple companies.

Most of the repo is a general pipeline, but the evaluation framework that's used heavily during model selection is specific to lead scoring. The evaluation framework measures the business value that a model (or heuristic) is expected to deliver assuming a world in which a company can only do outbound sales to a fraction of its lead universe and wants to rank leads by predicted revenue (or profit) value, conditional on acquisition.

Any users will need to add training data and adjust all files appropriately to reflect the label, the appropriate evaluation cutoffs, the features, and new winning model configuration.
