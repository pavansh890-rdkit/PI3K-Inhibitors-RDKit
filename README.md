# PI3K-Inhibitors Cheminformatics Analysis with RDKit
## 🧬 Project Overview
In silico evaluation of 10 PI3K inhibitors (anti-cancer target) for drug-likeness and structural similarity using RDKit.
This project was done as part of Cheminformatics assignment - from molecular visualization to Lipinski filtering and Tanimoto similarity.
## 🛠️ Tools Used
- Python, RDKit, Pandas, Seaborn, Matplotlib
- Google Colab
## 📊 Workflow
**Visualization:** Displayed 10 PI3K molecules in a 2x5 grid using `Draw.MolsToGridImage`
**Lipinski Descriptors:** Calculated MW, LogP, HBD, HBA, TPSA using Descriptors
**Drug-likeness:** Classified PASS/FAIL based on Lipinski's Rule of Five
**Fingerprints:** Generated Morgan Fingerprints (Radius 2, 2048 bits)
**Similarity:** Calculated Tanimoto Similarity Matrix and plotted heatmap
## ✅ Key Results
- **PASS (0 violations - Good oral drugs):** Mol_5, Mol_9, Mol_10
- **FAIL (1 violation - MW > 500):** Others - need optimization
- **Most Similar Pair:** Mol_3 & Mol_8 (Tanimoto = 0.90) - useful for SAR
## 📁 Files
- `PI3K_Analysis.ipynb` - Complete code and results
## 👨‍🔬 Author
Pavansh - Medicinal Chemist | 3.8 Years Synthesis Exp | MSc Pharmaceutical Chemistry
Focus: Cheminformatics, RDKit, PI3K Drug Design
GitHub: @pavansh890-rdkit
