# Structural Analysis of Rnc-Mrnc Complex (Nostoc punctiforme)

### **Project Overview**
This study provides a high-confidence structural model of the interaction between **RNase III (Rnc)** and its regulator **Mrnc**. This complex is vital for the stress response in cyanobacteria.

### **Structural Visualizations**

#### **1. Surface Complementarity (Shape Fit)**
![Surface View](Nostoc_Rnc_Mrnc_Interaction.png)
*Figure 1: Molecular surface of Mrnc (blue) docking into the Rnc (gray) catalytic domain.*

#### **2. Secondary Structure (Ribbon View)**
![Ribbon View](Nostoc_Rnc_Mrnc_Ribbons.png)
*Figure 2: Alignment of alpha-helices showing the internal structural 'handshake' between the two proteins.*

---
---
### **Methodology & Computational Workflow**

1. **Sequence Retrieval**: The protein sequences for **RNase III (Rnc)** and **Mrnc** were retrieved from the NCBI database for *Nostoc punctiforme* PCC 73102.
2. **Multiple Sequence Alignment (MSA)**: MSA was generated using the **MMseqs2** engine, achieving a sequence depth of 2,000. This provides a high evolutionary signal for folding.
3. **Structural Prediction**: The complex was modeled using **AlphaFold-Multimer (v1.5.5)** on the ColabFold platform.
4. **Visualization**: Secondary structure and molecular surface analysis were performed in **PyMOL** with ray-tracing for high-resolution detail.

---

