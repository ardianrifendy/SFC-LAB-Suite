# 🧪 SFC Lab Suite

Welcome to the **SFC Lab Suite** — the ultimate, premium single-file analytics tool specifically engineered for **Solid Fat Content (SFC)** laboratory analyses and blending predictions.

This application unites instrument data extraction, melting point prediction, blend calculations, historical database management, and differential analysis into a single, high-performance web interface.

---

## 🚀 Key Modules

The suite features 5 cohesive, high-fidelity analytics modules:

| Module | Description | Key Capabilities |
| :--- | :--- | :--- |
| **📥 Extractor** | Parses raw, messy instrument reports. | Supports both Single Definition (A) and Archive (B) logs. |
| **📈 Trend & MP** | Plots SFC curves and computes Melting Point (MP). | Intersects reference axes with precise decimal calculations. |
| **⚖️ Blend Calculator** | Simulates and predicts multi-component fat blends. | Visualizes prediction curves alongside reference targets. |
| **🗃️ Data Master** | Manages historical laboratory records. | Supports local storage auto-saving, Excel export/import, and manual reference overrides. |
| **🔍 Diff Viewer** | Analyzes deviations between predictions and lab trials. | Features custom tolerance settings and TSV quick-parsers. |

---

## 🛠️ How to Use

### Running the Application
Since the suite is fully compiled into a **self-contained single HTML file**, there are zero external dependencies or server setups required.
1. Open the file **`sfc-lab-suite.html`** in any modern web browser (Edge, Chrome, Safari, Firefox).
2. All data is saved automatically in your browser's local storage.

### Customizing the Default Database (Master Seed)
If you want to update the default reference database loaded at startup:
1. Open and edit the Excel-compatible **`data_master_seed.csv`**.
2. Recompile the suite by running the builder script in your terminal:
   ```bash
   node scratch/generate_suite.js
   ```
3. Open the app, navigate to **Data Master**, and click **🔄 Reset Database ke Seed** to apply the new defaults.

---

## 🎨 Premium Visual Elements
*   **Theme-Aware UI**: Toggle seamlessly between dynamic Light Mode and sleek Zinc Dark Mode.
*   **Interactive Components**: Zero native HTML controls — custom premium dropdown selectors, mid-screen confirmation modals, and responsive layout tables.
*   **Freeze Panes**: Fixed cross-headers on Data Master and Reference grids for smooth Excel-like scrolling.
*   **Strict Precision**: 2-decimal formatting throughout all grids for rigorous laboratory accuracy.
