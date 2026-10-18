<p align="center">
  <img src="https://raw.githubusercontent.com/FerAlLab-git/.github/main/profile/logo1.jpg" alt="FerAl Lab raccoon logo" width="180">
</p>

<h1 align="center">FerAl Lab</h1>

<p align="center">
  <b>Simulation and decision science for health policy</b><br>
  Department of Health Policy · Stanford University School of Medicine<br>
  Center for Health Policy · Freeman Spogli Institute for International Studies
</p>

---

## Who we are

FerAl Lab builds computer simulations that follow large virtual populations through their lifetimes, so decision makers can see which screening tests, treatments, and prevention programs to offer, to whom, when, and at what cost, before those choices reach patients. We work at the intersection of disease simulation, decision analysis, Bayesian statistics, and health economics, and we care as much about *how* a model is built (transparent, reproducible, open) as about the answer it gives.

The lab is led by [Fernando Alarid-Escudero](https://profiles.stanford.edu/fernando-alarid-escudero) and brings together PhD students, postdoctoral fellows, research software developers and programmers, and visiting trainees. Our members and collaborators work across the United States, Mexico, Chile, Canada, and Europe, and we mentor in both English and Spanish.

Our name joins **Fer**nando and **Al**arid, and our motto is *Stay feral*: curious, independent, and willing to explore beyond the usual trails.

## What we work on

- **Cancer control policy.** Microsimulation models of colorectal, gastric, and bladder cancer within NCI's CISNET, including work that informs U.S. Preventive Services Task Force evidence reviews. Current questions include blood-based screening tests, FIT positivity thresholds, follow-up after a positive screening test, and *H. pylori* screen-and-treat strategies.
- **Global health in Latin America.** How middle-income countries, especially Mexico and Chile, can build cancer screening programs that match what their health systems can deliver.
- **Methods for trustworthy models.** Bayesian calibration with machine-learning emulators, pre-calibration diagnostics, fast event-time sampling, value-of-information analysis, and models that represent social processes and health inequities.
- **Beyond cancer.** The same tools applied to COVID-19 (in Mexico and in U.S. prisons), dementia care, HIV prevention, and drug policy.
- **Open and AI-assisted modeling.** Free R tools, tutorials, and new ways of using AI to build, check, and reproduce decision models.

## Tools we build

| Tool | What it does |
|---|---|
| [**DESCIPHR**](https://link.springer.com/article/10.1007/s40273-025-01571-3) | Open-source discrete-event simulation framework for cancer interventions and population health in R, led by [Selina Pi](https://github.com/sjpi22) |
| [**BayCANN**](https://www.frontiersin.org/journals/physiology/articles/10.3389/fphys.2021.662314/full) | Bayesian calibration of simulation models using artificial neural network emulators. Co-developed with [Hawre Jalal](https://github.com/hjalal) and [Tom Trikalinos](https://github.com/ttrikalin)|
| [**Gaussian approximation (GA) for EVSI**](https://doi.org/10.1177/0272989X17715627) | Estimates the expected value of sample information from a single set of probabilistic sensitivity analysis results, without nested simulation. Co-developed with [Hawre Jalal](https://github.com/hjalal), used in applied value-of-information studies, and included in [ISPOR’s EVSI computation guidance](https://www.valueinhealthjournal.com/article/S1098-3015(20)30149-2/fulltext). Access the code here: [EVSI Gaussian Approximation](https://github.com/FerAlLab-git/VOI-Gaussian-Approximation) |
| [**dshr**](https://github.com/feralaes/dshr) | R package to derive disease-specific hazard ratios (dsHR) from the overall hazard ratios (oHR) reported in trials, so treatment effects can be applied correctly in models that already include background mortality |
| [**hhmcseirv**](https://github.com/SC-COSMO/hhmcseirv) | Multi-compartment SEIRSV transmission framework with non-exponential durations in the exposed and infectious states, tracking household and community transmission separately. Co-developed with [Jeremy Goldhaber-Fiebert](https://github.com/jeremygf), used in our [COVID-19 modeling analysis for Mexico City](https://doi.org/10.1177/23814683211049249) |
| [**PRE-CISE**](https://www.medrxiv.org/content/10.64898/2026.02.27.26346591v3) | Pre-calibration diagnostics for complex simulation models, led by [Valeria Gracia](https://github.com/vgraciaol) |
| [**dampack**](https://github.com/DARTH-git/dampack), [**darthtools**](https://github.com/DARTH-git/darthtools), [**darthpack**](https://github.com/DARTH-git/darthpack) | R packages and templates for decision-analytic modeling, developed with [DARTH](https://github.com/DARTH-git) |

## Code for our papers

R packages that reproduce the analyses in our publications.

| Package | Reproduces |
|---|---|
| [**cdx2cea**](https://github.com/feralaes/cdx2cea) | Cost-effectiveness of testing average-risk stage II colon cancer patients for the absence of CDX2 biomarker expression, followed by adjuvant chemotherapy |

## Tutorials

Peer-reviewed, step-by-step tutorials with open R code. A good place to start if you are new to decision modeling.

| Tutorial | Published |
|---|---|
| [A Tutorial on Discrete Event Simulation Models Using a Cost-Effectiveness Analysis Example in R](https://doi.org/10.1177/0272989X261437826), led by [Mauricio López-Méndez](https://github.com/LopezM-Mauricio) | *Medical Decision Making*, 2026 |
| [A Tutorial on Time-Dependent Cohort State-Transition Models in R using a Cost-Effectiveness Analysis Example](https://doi.org/10.1177/0272989X221121747) | *Medical Decision Making*, 2023 |
| [An Introductory Tutorial on Cohort State-Transition Models in R using a Cost-Effectiveness Analysis Example](https://doi.org/10.1177/0272989X221103163) | *Medical Decision Making*, 2023 |
| [A Multidimensional Array Representation of State-Transition Model Dynamics](https://doi.org/10.1177/0272989X19893973) | *Medical Decision Making*, 2020 |
| [A need for change! A coding framework for improving transparency in decision modeling](https://pubmed.ncbi.nlm.nih.gov/31549359/) | *PharmacoEconomics*, 2019 |
| [Microsimulation Modeling for Health Decision Sciences Using R: A Tutorial](https://doi.org/10.1177/0272989X18754513) | *Medical Decision Making*, 2018 |
| [An Overview of R in Health Decision Sciences](https://pubmed.ncbi.nlm.nih.gov/28061043/) | *Medical Decision Making*, 2017 |

Most of these were developed with the [DARTH workgroup](https://www.darthworkgroup.com/tutorials/).

## Publications

See the full list on [Fernando's Stanford profile](https://profiles.stanford.edu/fernando-alarid-escudero) or [Google Scholar](https://scholar.google.com/citations?user=i_1js6UAAAAJ&hl=en&oi=sra).

## Our groups and collaborations

Much of our code lives in the GitHub organizations of the groups we lead, co-founded, or belong to.

### Groups we lead or co-founded

| Organization | What it is |
|---|---|
| [**SimCRC**](https://github.com/SimCRC) | Simulation Model of Colorectal Cancer, one of the NCI CISNET colorectal cancer models |
| **DESCIPHR-GC** *(coming soon)* | Gastric cancer microsimulation model for the NCI CISNET Gastric Cancer consortium |
| [**DARTH-git**](https://github.com/DARTH-git) | Decision Analysis in R for Technologies in Health, a multi-institutional collaborative for open-source decision modeling in R (co-founded in 2015) |
| [**IMPACCT-Stanford**](https://github.com/IMPACCT-Stanford) | International Modeling for Policy Analysis in Cancer Control and Translation |
| [**ConVOI**](https://github.com/convoigroup) | Collaborative Network for Value of Information, producing open tools and guidance for value-of-information analysis |

### Consortia we are part of

| Organization | What it is |
|---|---|
| [**NCI-CISNET**](https://github.com/NCI-CISNET) | The Cancer Intervention and Surveillance Modeling Network, NCI's consortium of cancer simulation modelers |
| [**NCI-CISNET-Colorectal**](https://github.com/NCI-CISNET-Colorectal) | CISNET Colorectal Cancer working group |
| [**NCI-CISNET-Gastric**](https://github.com/NCI-CISNET-Gastric) | CISNET Gastric Cancer working group |
| [**CISNET-Bladder-Cancer**](https://github.com/bladder-ca) | CISNET Bladder Cancer working group |
| [**CISNET-COBRAS**](https://github.com/CISNET-COBRAS) | COBRAS bladder cancer model within CISNET Bladder |

This organization, **FerAlLab-git**, is home to lab-wide work: methods, tutorials, trainee projects, and reproducible code for our papers.

## How we work

- **Open by default.** Code, data (when we can share it), and documentation accompany our papers.
- **Reproducible.** Version control, code review, and documented pipelines for every project.
- **R first.** Most of our tools are written in R, with C++ or other languages where speed requires it.
- **Built for decisions.** We design models to answer questions that guideline panels, ministries of health, and clinicians actually face.

## Funding

Our work is supported by the National Cancer Institute through CISNET (U01CA319117, U01CA319219, U01CA319218), the National Institute on Drug Abuse (R37DA015612), and Stanford Impact Labs, among others.

## Get in touch

Using one of our tools or found a bug? Please open an issue in that tool's repository so the answer helps everyone. For research collaborations, contact [falarid@stanford.edu](mailto:falarid@stanford.edu).

<p align="center"><i>🦝 Stay feral.</i></p>
