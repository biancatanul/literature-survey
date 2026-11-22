# Saleiro2018: Aequitas: A Bias and Fairness Audit Toolkit

- **Type:** tool paper
- **Priority:** primary
- **Reference:** see `references.bib`, key `Saleiro2018`

## Summary

Aequitas is an open-source audit toolkit meant to slot into the ML workflow, so models can be tested against several bias and fairness metrics. It focuses on fairness of impact, meaning the predictions, using parity-based measures. The audit needs a pandas dataframe with a label, a score and one or more sensitive attribute columns. Offered as a Python library, a command-line tool and a web application.

Link: https://datasciencepublicpolicy.org/our-work/tools-guides/aequitas/

## Use in my thesis

Similar tool and source of metrics. Take the reference-group plus threshold logic for disparity ratios, and compare its required input (label and score) with my plan to accept raw datasets.
