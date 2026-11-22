# Literature survey: bias detection and visualization in datasets and models

This repository collects the literature considered for my BSc thesis, with notes on what each source contributes.

## Contents

- `references.bib`: full bibliographic information of all sources (managed with JabRef)
- `papers/`: PDFs, named after the BibTeX key (see the access notes below)
- `notes/`: one note per source (type, summary, and how it is used in the thesis)

## Access and PDFs

Since not every source can legally be redistributed, the PDF column of each table says what is in `papers/`:

- **Open access:** free to read and reuse. The PDF is included (or, for books and datasets, linked).
- **Free to read on publisher site:** the PDF can be downloaded from the publisher or proceedings site without a login, but it may not carry an open licence, so reuse terms are the publisher's. The PDF in the repo is the one from that site.
- **Not open access:** the published version is behind a paywall or an institutional login, or I could not confirm it is free. Where an arXiv preprint exists, that preprint is the PDF in the repo. The preprint can differ slightly from the published version (title, layout, page numbers), so the thesis cites the published version and its DOI is given in the last column.
- **Link only:** no free full text found, so no PDF is included. Use the DOI to access it.

The last column of every table links the original full paper (publisher page or DOI).

## How to read the notes

- **Priority:** primary (directly used in the state of the art or the design), secondary (supporting background), edge (related area, cited briefly).
- Each note has a summary of the source and a 'Use in my thesis' section saying what is relevant and for what.

## Sources by theme

### Closest work

| Key | Title | Access | PDF in repo | Original paper |
|---|---|---|---|---|
| [Lavalle2020](notes/Lavalle2020.md) | An Approach to Automatically Detect and Visualize Bias in Data Analytics | Open access | [pdf](papers/Lavalle2020.pdf), publisher PDF | [link](https://ceur-ws.org/Vol-2572/short11.pdf) |
| [Lavalle2023](notes/Lavalle2023.md) | A Data Analytics Methodology to Visually Analyze the Impact of Bias and Rebalancing | Open access | [pdf](papers/Lavalle2023.pdf), publisher PDF | [link](https://doi.org/10.1109/ACCESS.2023.3279732) |

### Surveys and background

| Key | Title | Access | PDF in repo | Original paper |
|---|---|---|---|---|
| [Mehrabi2021](notes/Mehrabi2021.md) | A Survey on Bias and Fairness in Machine Learning | Free to read on publisher site | [pdf](papers/Mehrabi2021.pdf), publisher PDF (ACM) | [link](https://doi.org/10.1145/3457607) |
| [Pessach2022](notes/Pessach2023.md) | A Review on Fairness in Machine Learning | Free to read on publisher site | [pdf](papers/Pessach2023.pdf), publisher PDF (ACM) | [link](https://doi.org/10.1145/3494672) |
| [Caton2024](notes/Caton2024.md) | Fairness in Machine Learning: A Survey | Free to read on publisher site | [pdf](papers/Caton2024.pdf), publisher PDF (ACM) | [link](https://doi.org/10.1145/3616865) |
| [Pagano2023](notes/Pagano2023.md) | Bias and Unfairness in Machine Learning Models: A Systematic Review on Datasets, Tools, Fairness Metrics, and Identification and Mitigation Methods | Open access | [pdf](papers/Pagano2023.pdf), publisher PDF | [link](https://doi.org/10.3390/bdcc7010015) |
| [Gallegos2024](notes/Gallegos2024.md) | Bias and Fairness in Large Language Models: A Survey | Open access | [pdf](papers/Gallegos2024.pdf), publisher PDF | [link](https://doi.org/10.1162/coli_a_00524) |
| [He2009](notes/He2009.md) | Learning from Imbalanced Data | Not open access | none (link only) | [link](https://doi.org/10.1109/tkde.2008.239) |

### Definitions and metrics

| Key | Title | Access | PDF in repo | Original paper |
|---|---|---|---|---|
| [Verma2018](notes/Verma2018.md) | Fairness Definitions Explained | Free to read on publisher site | [pdf](papers/Verma2018.pdf), publisher PDF (ACM) | [link](https://doi.org/10.1145/3194770.3194776) |
| [Hardt2016](notes/Hardt2016.md) | Equality of Opportunity in Supervised Learning | Free to read on publisher site | [pdf](papers/Hardt2016.pdf), publisher PDF (NeurIPS proceedings) | [link](https://papers.nips.cc/paper/6374-equality-of-opportunity-in-supervised-learning) |
| [Dwork2012](notes/Dwork2012.md) | Fairness through Awareness | Free to read on publisher site | [pdf](papers/Dwork2012.pdf), publisher PDF (ACM) | [link](https://doi.org/10.1145/2090236.2090255) |

### Toolkits

| Key | Title | Access | PDF in repo | Original paper |
|---|---|---|---|---|
| [Saleiro2018](notes/Saleiro2018.md) | Aequitas: A Bias and Fairness Audit Toolkit | Open access | [pdf](papers/Saleiro2018.pdf), arXiv (the paper is only published there) | [link](https://arxiv.org/abs/1811.05577) |
| [Bellamy2019](notes/Bellamy2019.md) | AI Fairness 360: An Extensible Toolkit for Detecting and Mitigating Algorithmic Bias | Not open access | [pdf](papers/Bellamy2019.pdf), arXiv preprint (earlier title: Detecting, Understanding, and Mitigating Unwanted Algorithmic Bias) | [link](https://doi.org/10.1147/jrd.2019.2942287) |
| [Weerts2023](notes/Weerts2023.md) | Fairlearn: Assessing and Improving Fairness of AI Systems | Open access | [pdf](papers/Weerts2023.pdf), publisher PDF | [link](https://jmlr.org/papers/v24/23-0389.html) |
| [Wexler2020](notes/Wexler2020.md) | The What-If Tool: Interactive Probing of Machine Learning Models | Free to read on publisher site | [pdf](papers/Wexler2020.pdf), publisher PDF (IEEE) | [link](https://doi.org/10.1109/TVCG.2019.2934619) |

### Visual tools

| Key | Title | Access | PDF in repo | Original paper |
|---|---|---|---|---|
| [Cabrera2019](notes/Cabrera2019.md) | FairVis: Visual Analytics for Discovering Intersectional Bias in Machine Learning | Not open access | [pdf](papers/Cabrera2019.pdf), arXiv preprint | [link](https://doi.org/10.1109/VAST47406.2019.8986948) |
| [Ahn2020](notes/Ahn2020.md) | FairSight: Visual Analytics for Fairness in Decision Making | Not open access | [pdf](papers/Ahn2020.pdf), arXiv preprint | [link](https://doi.org/10.1109/tvcg.2019.2934262) |
| [Munechika2022](notes/Munechika2022.md) | Visual Auditor: Interactive Visualization for Detection and Summarization of Model Biases | Not open access | [pdf](papers/Munechika2022.pdf), arXiv preprint | [link](https://doi.org/10.1109/vis54862.2022.00018) |
| [Wang2022](notes/Wang2022.md) | REVISE: A Tool for Measuring and Mitigating Bias in Visual Datasets | Not open access | [pdf](papers/Wang2022.pdf), arXiv preprint (v4) | [link](https://doi.org/10.1007/s11263-022-01625-5) |

### Human studies

| Key | Title | Access | PDF in repo | Original paper |
|---|---|---|---|---|
| [Deng2022](notes/Deng2022.md) | Exploring How Machine Learning Practitioners (Try To) Use Fairness Toolkits | Open access | [pdf](papers/Deng2022.pdf), publisher PDF (ACM)| [link](https://doi.org/10.1145/3531146.3533113) |
| [Lee2021](notes/Lee2021.md) | The Landscape and Gaps in Open Source Fairness Toolkits | Open access | [pdf](papers/Lee2021.pdf), publisher PDF | [link](https://doi.org/10.1145/3411764.3445261) |
| [Saha2020](notes/Saha2020.md) | Measuring Non-Expert Comprehension of Machine Learning Fairness Metrics | Free to read on publisher site | [pdf](papers/Saha2020.pdf), publisher PDF | [link](https://proceedings.mlr.press/v119/saha20c.html) |
| [Dodge2019](notes/Dodge2019.md) | Explaining Models: An Empirical Study of How Explanations Impact Fairness Judgment | Free to read on publisher site | [pdf](papers/Dodge2019.pdf), publisher PDF (ACM) | [link](https://doi.org/10.1145/3301275.3302310) |
| [Wall2026](notes/Wall2026.md) | Human Bias in Visual Data Analysis: A Synthesis of Research to Empower Decision Makers | Open access | [pdf](papers/Wall2026.pdf)  | [link](https://link.springer.com/book/10.1007/978-3-032-09307-3) |

### Data

| Key | Title | Access | PDF in repo | Original paper |
|---|---|---|---|---|
| [LeQuy2022](notes/LeQuy2022.md) | A Survey on Datasets for Fairness-aware Machine Learning | Open access | [pdf](papers/LeQuy2022.pdf), publisher PDF | [link](https://doi.org/10.1002/widm.1452) |
| [Chen2018](notes/Chen2018.md) | Why Is My Classifier Discriminatory? | Free to read on publisher site | [pdf](papers/Chen2018.pdf), publisher PDF (NeurIPS proceedings) | [link](https://proceedings.neurips.cc/paper_files/paper/2018/file/1f1baa5b8edac74eb4eaa329f14a0361-Paper.pdf) |
| [Becker1996](notes/Becker1996.md) | Adult (UCI Machine Learning Repository) | Open data (CC BY 4.0) | none (dataset, see link) | [link](https://doi.org/10.24432/C5XW20) |
| [Hofmann1994](notes/Hofmann1994.md) | Statlog (German Credit Data) (UCI Machine Learning Repository) | Open data (CC BY 4.0) | none (dataset, see link) | [link](https://doi.org/10.24432/C5NC77) |