# Network Analysis of Organizational Email Communication
## Email-Eu-Core Network Study

**Course:** DASC-5260 Network Science  
**Author:** Mureed Sajjad Mirjat  
**Institution:** University of Sindh, Jamshoro, Pakistan  
**Instructor:** Dr. Abdul Waheed Mahesar  
**Grade:** 10 / 10  
**Date:** December 2024

---

## Overview

This project applies complex network analysis to the Email-Eu-core 
dataset from the Stanford Network Analysis Project (SNAP), which 
captures 25,571 directed email exchanges among 1,005 employees 
at a European research institution.

The analysis uncovers structural properties of organizational 
communication, including degree distribution, network density, 
clustering coefficients, betweenness centrality, closeness 
centrality, assortativity, and eigenvector centrality.

The full written report was evaluated as research quality by the 
course instructor and received full marks.

---

## Dataset

- **Name:** Email-Eu-Core Network
- **Source:** Stanford Network Analysis Project (SNAP)
- **Link:** http://snap.stanford.edu/data/email-Eu-core.html
- **Nodes:** 1,005 employees
- **Edges:** 25,571 directed email communications
- **Period:** October 2003 to May 2005
- **Type:** Directed, unweighted graph

---

## Key Findings

| Metric | Value |
|---|---|
| Network Density | 0.0253 (sparse) |
| Average Degree | 50.89 |
| Maximum Degree | 546 |
| Global Clustering Coefficient | 0.2674 |
| Average Local Clustering | 0.3994 |
| Maximum Betweenness Centrality | 0.072121 |
| Maximum Closeness Centrality | 0.584917 |

**Key result:** Node 160 demonstrates the highest betweenness 
centrality and highest closeness centrality simultaneously, 
identifying it as the most strategically critical node in the 
network, functioning as both an information broker and a 
rapid dissemination hub.

**Network topology:** Scale-free degree distribution with 
disassortative mixing, consistent with hierarchical 
organizational communication structures.

---

## Metrics Computed

- Degree centrality (in-degree, out-degree, total degree)
- Network density
- Global and local clustering coefficients
- Betweenness centrality (normalized)
- Closeness centrality (normalized)
- Assortativity coefficient (theoretical analysis)
- Eigenvector centrality (theoretical analysis)

---

## Visualisations Produced

- Degree distribution (in, out, total) histograms
- Local clustering coefficient distribution
- Betweenness centrality distribution
- Closeness centrality distribution
- Network graph filtered for nodes with degree above 20,
  with node size and colour proportional to connectivity

---

## Repository Contents
email-network-analysis/
│
├── Network_Science_Analysis.R        # Full R analysis script
├── Report.pdf                        # Complete written report
├── images/                           # Generated visualisations
│   ├── degree_distribution.png
│   ├── clustering_distribution.png
│   ├── betweenness_distribution.png
│   ├── closeness_distribution.png
│   └── network_visualization.png
└── README.md

---

## Technologies and Tools

- **Language:** R
- **Packages:** igraph, ggplot2, ggraph, gridExtra,
  RColorBrewer, dplyr, readr
- **Environment:** RStudio

---

## How to Run

1. Download the Email-Eu-core dataset from SNAP:
   http://snap.stanford.edu/data/email-Eu-core.html

2. Place `email-Eu-core.txt` in your working directory

3. Open `Network_Science_Analysis.R` in RStudio

4. Update the `setwd()` path to match your directory

5. Run all code blocks sequentially

The script will generate all visualisations and a 
metrics summary CSV automatically.

---

## References

Key references used in the analysis:

- Newman, M.E.J. (2003). The structure and function of 
  complex networks. SIAM Review, 45(2), 167-256.
- Watts, D.J. and Strogatz, S.H. (1998). Collective dynamics 
  of small-world networks. Nature, 393, 440-442.
- Barabasi, A.L. and Bonabeau, E. (2003). Scale-free networks. 
  Scientific American, 288(5), 50-59.
- Freeman, L.C. (1977). Centrality based on betweenness. 
  Sociometry, 40(1), 35-41.

Full reference list available in Report.pdf.

---

## Author

**Mureed Sajjad Mirjat**  
Final Year Data Science Student  
University of Sindh, Jamshoro  
Khairpur, Sindh, Pakistan  

[LinkedIn](https://linkedin.com/in/mureed-sajjad) |
[GitHub](https://github.com/MureedSajjad)
