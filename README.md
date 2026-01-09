# MSc Project – Functional Attrition, Multistate Modeling, and QoL Prediction  
### (Secondary Analysis of Trial NCT02349412)

This repository contains all code, outputs, and reproducible workflows for my MSc project in Biostatistics and Epidemiology. The project investigates **functional attrition** in longitudinal patient-reported outcomes and evaluates how **missing-data handling methods** (MICE vs IPCW) affect predictive model calibration and performance.

---

## 📁 Repository Structure

### **Main RMarkdown Workflows (Root Folder)**

- **01_Data Preparation & Descriptive Analysis.Rmd**  
  Data cleaning, preprocessing, and descriptive statistics.

- **02_multistate_modeling.Rmd**  
  Multistate modeling of transitions between active participation, functional attrition, and death.

- **03_prediction_and_comparison.Rmd**  
  Prediction modeling and comparison of MICE vs IPCW approaches.

Other files include `.Rproj` project settings and the `_site.yml` configuration for HTML rendering.

---

## 📁 Output Directories

Each workflow writes its results into a dedicated folder:

- `Data_Preparation_&_Descriptive_output/` – descriptive tables and figures  
- `output_multistate/` – transition probabilities, graphs, multistate outputs  
- `outputs_prediction_IPCW/` – IPCW predictions + diagnostics  
- `results_prediction_MICE/` – MICE prediction results  
- `results_impute_nested/` – nested multiple imputation results  
- `results_mnar/` – MNAR sensitivity analyses

---

## 🌐 HTML Reports (Folder: `_site/`)
The folder `_site/` contains the knitted HTML versions of all `.Rmd` files:

_site/

├── 01_Data-Preparation---Descriptive-Analysis.html

├── 02_multistate_modeling.html

├── 03_prediction_and_comparison.html

└── site_libs/

### 🔍 How to View  
GitHub **cannot** display HTML directly. To open them:

1. Click **Code → Download ZIP**
2. Extract the folder
3. Open: MSc_project/_site/
4. Double-click any HTML file  
   → It will open in your web browser.

---

## 🔧 Reproducibility

### Requirements
- **R ≥ 4.2**
- Recommended packages:  
  `tidyverse`, `mice`, `survival`, `mstate`, `ggplot2`, `rms`, `ipw`, `knitr`, `rmarkdown`

### To Reproduce the Whole Pipeline
1. Open: Summer_project.Rproj
2. Knit the workflow files **in order**:
  01_Data Preparation & Descriptive Analysis.Rmd
  02_multistate_modeling.Rmd
  03_prediction_and_comparison.Rmd

Outputs will automatically appear in the corresponding folders.

---

## 📣 Citation
If you reuse this workflow or code, please cite:
**Gayi S.K. (2025). MSc Project – Functional Attrition and QoL Prediction in Advanced Cancer (NCT02349412). GitHub Repository.**

📬 Contact
For questions, collaboration, or feedback, feel free to contact:
Selassi Komi GAYI
Corresponding Author
Email: kg2083@srmist.edu.in | gayikomiselassi@gmail.com
ORCID: 0009-0006-3598-4224

---
