# 🧬 Breast Cancer Top 30 Hub Genes – Drug-Gene Interaction Network

![Network Analysis](https://img.shields.io/badge/Analysis-Network_Biology-blue)
![Tool](https://img.shields.io/badge/Tool-Cytoscape-orange)
![Project Status](https://img.shields.io/badge/Status-Active-success)
![Cancer Type](https://img.shields.io/badge/Disease-Breast_Cancer-pink)
![Focus](https://img.shields.io/badge/Focus-Hub_Genes-important)

> A targeted **Cytoscape network analysis** isolating the **Top 30 Hub Genes in Breast Cancer** based on **degree centrality** to identify high-priority **drug-gene interactions** and **therapeutic vulnerabilities**.

---

# 📌 Overview

This repository contains an **advanced network analysis** focusing on the **top 30 most highly connected hub genes** within a **breast cancer drug-gene interaction network**.

The **network topology** was analyzed and visualized using **Cytoscape**, enabling the identification of **critical therapeutic targets** and highly connected biological regulators within the interaction network.

---

# 🧬 Project Context

Following an **initial broad network analysis**, this project filters the dataset to focus exclusively on **nodes with the highest Degree centrality**.

In **biological networks**, these highly connected **hub genes** often represent:

- 🔬 Essential regulatory bottlenecks  
- 🧬 Key disease-driving molecular components  
- 💊 High-value therapeutic intervention points  

By mapping **pharmacological agents** against these **30 hub genes**, this analysis prioritizes the **most impactful drug-gene interactions** for potential therapeutic development.

---

# 📂 Repository Contents

This repository includes the **complete Cytoscape session**, **raw interaction data**, and **network visualizations**.

### 📁 Files Included

- **`Breast_Cancer_DGI_with_Top30.cys`**

  **Description:**  
  The full **Cytoscape session file** containing:

  - Network data
  - Visual styles
  - Degree centrality calculations

---

- **`gene_interaction_results-27_2_2026.tsv_Degree_top30.sif`**

  **Description:**  
  A **Simple Interaction Format (SIF)** file defining the **nodes and edges** representing the **top 30 hub genes and their interacting drugs**.

---

- **`gene_interaction_results-27_2_2026.tsv_Degree_top30.pdf`**

  **Description:**  
  A **high-resolution network visualization** exported from Cytoscape highlighting:

  - Central hub genes
  - Drug interaction nodes
  - Highly targeted biological pathways

---

# ⚙️ Methodology

The network analysis followed a structured pipeline:

### 1️⃣ Centrality Calculation

Network topology was analyzed to calculate **node degree centrality** for **all genes in the dataset**.

Degree centrality identifies nodes with the **highest number of interactions**, which often correspond to **biologically important regulators**.

---

### 2️⃣ Hub Gene Isolation

The interaction network was **filtered** to extract the **Top 30 genes** with the **highest interaction degree**.

These genes represent the **most connected molecular components** in the breast cancer drug-gene interaction network.

---

### 3️⃣ Targeted Visualization

Within **Cytoscape**, custom **visual styles** were applied to:

- Differentiate **hub gene nodes**
- Highlight **drug interaction nodes**
- Improve **network readability**

The layout was optimized to emphasize the **most druggable hub genes** and **therapeutically relevant pathways**.

---

# 🚀 Tools Used

| Tool | Purpose |
|-----|------|
| **Cytoscape** | Network visualization and analysis |
| **Drug-Gene Interaction Data** | Interaction mapping |
| **Network Centrality Analysis** | Hub gene identification |

---

# 🎯 Research Significance

This project helps identify:

- 🧬 **Critical hub genes in breast cancer**
- 💊 **Potential drug targets**
- 🔬 **Highly connected molecular pathways**
- 📊 **Network-level therapeutic vulnerabilities**

These insights support **targeted drug discovery** and **systems biology approaches** for cancer research.

---

# 📜 License

This project is intended for **academic and research purposes**.

---

# ⭐ If You Find This Useful

Consider **starring the repository** and sharing it with researchers working in:

- Cancer Bioinformatics  
- Systems Biology  
- Network Medicine  
- Drug Discovery  
