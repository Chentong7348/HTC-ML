GBDT–SHAP Framework for Co-Optimized Hydrothermal Carbonization

Datasets, training/evaluation scripts, and deployment code accompanying the manuscript submitted to *Bioresource Technology*.

Three independent Gradient Boosting Decision Tree (GBDT) models — one per product stream — were trained on **1,062 literature records** to predict:

- **Hydrochar yield** (Dataset #HC, n = 670, wt% dry basis)
- **Aqueous-phase total nitrogen, TN** (Dataset #AP, n = 220, g N L⁻¹)
- **Carbon-dot fluorescence quantum yield, QY** (Dataset #CDs, n = 172, %)

Model interpretation relies on SHAP analyses; robustness is supported by a grid-based grouped five-fold cross-validation and by an independent 45-record external validation through the deployed web application.

---

## Web application

- **Online app (no installation):** https://my-permanent-app-2026.streamlit.app/
- **Offline Windows x64 build:** see [**Releases**](../../releases) — download the zip, unzip, and run the `.exe`; no Python environment required. An offline user guide is included in the package.
