# breast-cancer-top30-hub-genes
"A targeted Cytoscape network analysis isolating the top 30 hub genes in breast cancer based on degree centrality to identify high-priority drug-gene interactions and therapeutic vulnerabilities."
# Top 30 Hub Genes: Drug-Gene Interaction Network

## Overview
This repository contains the advanced network analysis focusing on the top 30 most highly connected hub genes within a breast cancer drug-gene interaction network. The network topology was analyzed and visualized using [Cytoscape](https://cytoscape.org/) to isolate critical therapeutic targets.

## Project Context
Following an initial broad network analysis, this project filters the dataset to focus exclusively on the nodes with the highest "Degree" centrality. In biological networks, these highly connected hub genes often represent essential regulatory bottlenecks or critical vulnerabilities in disease progression. By mapping pharmacological agents against these specific 30 targets, this analysis prioritizes the most impactful drug-gene interactions for potential therapeutic intervention.

## Repository Contents
This repository includes the complete Cytoscape session, the raw interaction data for the filtered network, and the exported visual representations:

* **`Breast_Cancer_DGI_with_Top30.cys`**: The full Cytoscape session file containing the network data, visual styles, and degree centrality calculations.
* **`gene_interaction_results-27_2_2026.tsv_Degree_top30.sif`**: The Simple Interaction Format (SIF) file defining the specific nodes and edges for the isolated top 30 hub genes and their interacting drugs.
* **`gene_interaction_results-27_2_2026.tsv_Degree_top30.pdf`**: A high-resolution PDF export of the Cytoscape network visualization, highlighting the central nodes and heavily targeted pathways.

## Methodology
1. **Centrality Calculation**: Network topology was analyzed to calculate node degree centrality for all genes in the broader dataset.
2. **Hub Gene Isolation**: The network was filtered to extract only the top 30 genes with the highest number of interactions (highest degree).
3. **Targeted Visualization**: Visual styles were applied within Cytoscape to clearly differentiate between the top 30 gene nodes and their corresponding drug nodes, optimizing the layout to emphasize the most druggable hubs.
