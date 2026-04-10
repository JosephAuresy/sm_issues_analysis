# SWAT-MODFLOW Community Issue Analysis

**Author:** David Serrano  
**Status:** Pre-publication research — for academic review  
**Advisor:** Dr. Seonggyu Park (Texas Tech University / SWAT-MODFLOW developer)  
**Date:** April 2026

---

## Overview

This repository contains a systematic scientific analysis of user-reported issues in the [SWAT-MODFLOW Google Group](https://groups.google.com/g/swat-modflow), covering approximately 409 discussion threads from 2015 to 2025.

The analysis was conducted as part of ongoing PhD research on coupled surface water–groundwater modelling. It applies a grounded theory coding methodology (open coding → axial coding → taxonomy) to classify, quantify, and propose systematic solutions for the recurring problems faced by the SWAT-MODFLOW user community worldwide.

The findings are intended to support:
- A peer-reviewed publication targeting **Environmental Modelling & Software** (Elsevier)
- Improvements to the **QSWATMOD2** graphical interface and workflow documentation
- A referenceable knowledge base for future SWAT-MODFLOW users and researchers

---

## Repository Contents

| File | Description |
|------|-------------|
| `index.html` | Interactive analysis dashboard (GitHub Pages ready) |
| `README.md` | This document |

---

## How to View

### Online (GitHub Pages)
Once deployed, the analysis is accessible at:
```
https://[your-github-handle].github.io/swat-modflow-analysis
```

### Locally
Clone the repository and open `index.html` in any modern web browser. No dependencies or build steps required.

```bash
git clone https://github.com/[your-github-handle]/swat-modflow-analysis.git
cd swat-modflow-analysis
open index.html   # macOS
# or
start index.html  # Windows
```

---

## Methodology Summary

Issues were classified using a two-pass coding scheme inspired by grounded theory:

1. **Open coding** — each thread assigned a preliminary descriptor based on title and content
2. **Axial coding** — descriptors merged into 8 parent categories with causal relationships identified
3. **Taxonomy** — each category assigned a type (procedural / theoretical / configuration / software bug), frequency count, priority level, and systematic solution

**Classification dimensions:**

| Dimension | Values |
|-----------|--------|
| Nature | Procedural · Theoretical · Config/File · Software Bug |
| Priority | High · Medium · Low |
| Resolvability | Documentation fix · Code fix · Research needed |
| Frequency | Estimated thread count per category |

---

## Issue Categories (Summary)

| ID | Category | ~Threads | Type | Priority |
|----|----------|----------|------|----------|
| CAT-01 | Model Linking & Coupling Setup | 120 | Procedural | HIGH |
| CAT-02 | MODFLOW Convergence Failures | 95 | Theoretical | HIGH |
| CAT-03 | Simulation Crashes & Runtime Errors | 82 | Procedural + Bug | HIGH |
| CAT-04 | Recharge & SW-GW Exchange Outputs | 68 | Theoretical | HIGH |
| CAT-05 | Calibration & Parameter Sensitivity | 53 | Theoretical | MEDIUM |
| CAT-06 | QSWATMOD2 GUI & Plugin Errors | 41 | Software Bug | MEDIUM |
| CAT-07 | Temporal/Spatial Discretization Mismatch | 33 | Config | MEDIUM |
| CAT-08 | Advanced Features (RT3D, Irrigation) | 17 | Mixed | LOW |

---

## Intended Publication

> **Working title:** *A Systematic Analysis of User-Reported Issues in SWAT-MODFLOW: Classification, Frequency, and Guidance for Coupled Hydrological Modelling*
>
> **Target journal:** Environmental Modelling & Software (Elsevier)  
> **Type:** Methods / Perspective article  
> **Authors (proposed):** David Serrano, Seonggyu Park

This analysis constitutes the observational foundation for the paper. The full manuscript is in preparation.

---

## Citation

Until formal publication, please cite this work as:

```
Serrano, D. (2026). Systematic Analysis of User-Reported Issues in SWAT-MODFLOW:
Classification, Frequency, and Proposed Solutions. Pre-publication research report.

```

---

## License

Copyright © 2026 David Serrano. All rights reserved.

This work is shared for **academic review purposes only** under the following terms:

- ✅ Viewing, reading, and evaluating the content is permitted
- ✅ Sharing the repository link with academic colleagues is permitted
- ✅ Citing this work in academic publications (with attribution) is permitted
- ❌ Redistribution, reproduction, or derivative works are **not permitted** without explicit written consent from the author
- ❌ Commercial use of any kind is **not permitted**

This pre-publication license will be updated upon formal publication. For permissions or collaboration enquiries, please contact the author directly.

---

## Contact

**David Serrano**  
PhD Student
[Texas Tech University / Department of Civil and Environmental Engineering]  
📧 [davidser@ttu.edu]  
🔗 [[LinkedIn](https://www.linkedin.com/in/david-serrano-suarez/?originalSubdomain=ca)]

**Advisor: Dr. Seonggyu Park**  
Developer, SWAT-MODFLOW & QSWATMOD2  
Texas Tech University  
🔗 https://github.com/spark-hydro/

---

## Acknowledgements

This research builds on the foundational work of Dr. Seonggyu Park and Dr. Ryan Bailey in developing SWAT-MODFLOW and QSWATMOD2. The analysis data is derived from the public SWAT-MODFLOW Google Group community, whose members' questions and experiences make this study possible.

Key references:
- Bailey, R.T. et al. (2016). *Assessing Regional-Scale Spatio-Temporal Patterns of Groundwater-Surface Water Interactions using a Coupled SWAT-MODFLOW Model.* Hydrological Processes. https://doi.org/10.1002/hyp.10933
- Park, S. et al. (2018). *A QGIS-based graphical user interface for application and evaluation of SWAT-MODFLOW models.* Environmental Modelling & Software. https://doi.org/10.1016/j.envsoft.2018.10.017
- Harbaugh, A.W. (2005). *MODFLOW-2005, the U.S. Geological Survey modular ground-water model.* USGS Techniques and Methods.
