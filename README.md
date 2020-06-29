MTB Virulence Factors Analysis - Final Year Project
Project Overview
Comprehensive analysis of Mycobacterium tuberculosis virulence factors and drug resistance patterns using bioinformatics and computational approaches. This project was completed as a final year capstone project in June 2020.

Problem Statement
Mycobacterium tuberculosis remains a significant global health threat, causing approximately 10 million new tuberculosis cases worldwide in 2018. The bacterium's sophisticated virulence mechanisms and evolving drug resistance pose major challenges to treatment and eradication efforts. This project addresses the critical need to understand the molecular basis of MTB virulence and drug resistance.

Objectives
Provide in-depth coverage of major virulence factors in Mycobacterium tuberculosis

Identify genes responsible for resistance to anti-TB drugs

Analyze mutation patterns across MTB genomes to identify mutation-prone regions

Develop predictive models for drug resistance based on virulence factors

Create genome topology networks for virulence factor interaction analysis

Technologies and Tools Used
Programming: Python 3.7

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Biopython, NetworkX

Bioinformatics Tools: NCBI BLAST, Custom sequence analysis pipelines

Databases: VFDB (Virulence Factor Database), TBDReaMDB (TB Drug Resistance Mutation Database), PHIDIAS/Victors, SwissProt

Methodologies: Machine Learning, Statistical Analysis, Network Analysis, Genomic Data Mining

Dataset
50 Mycobacterium tuberculosis strains from NCBI

Virulence factor data from VFDB and Victors databases

Drug resistance mutation patterns from TBDReaMDB

Protein-protein interaction data from PHIDIAS

Annotated genomic sequences from multiple MTB lineages

Methodology
Data Collection: Downloaded and curated MTB genomes from NCBI database

Sequence Analysis: Performed BLAST searches against virulence factor databases

Mutation Screening: Identified and characterized drug resistance mutations

Network Construction: Built genome topology networks for orthologous groups

Statistical Analysis: Conducted correlation analysis between virulence factors and drug resistance

Machine Learning: Implemented Random Forest classifier for resistance prediction

Visualization: Created comprehensive plots and network diagrams

Key Findings
rpoB mutations identified as the primary predictor of rifampicin resistance (70% correlation)

katG mutations strongly associated with isoniazid resistance

Combination of rpoB and katG mutations highly predictive of multi-drug resistant TB (MDR-TB)

Machine learning model achieved 85% accuracy in predicting drug resistance

Geographical variations observed in virulence factor distribution

ESX secretion systems and PDIM lipids identified as key virulence mechanisms

Network analysis revealed interconnected virulence factor clusters

Project Structure
text
mtb-virulence-analysis/
├── mtb_virulence_analysis.py    # Main analysis code
├── requirements.txt             # Python dependencies
├── README.md                   # Project documentation
├── project_report.pdf          # Detailed project report
├── setup_github.sh            # Repository setup script
└── .gitignore                 # Git ignore rules
Installation and Execution
Prerequisites
Python 3.7 or higher

pip package manager

Setup Instructions
Clone the repository:

bash
git clone https://github.com/your-username/mtb-virulence-analysis-2020.git
cd mtb-virulence-analysis
Install required packages:

bash
pip install -r requirements.txt
Run the analysis:

bash
python mtb_virulence_analysis.py
Dependencies
The project requires the following Python packages (specific versions from 2020):

pandas==1.0.5

numpy==1.18.5

matplotlib==3.2.2

seaborn==0.10.1

scikit-learn==0.22.2

biopython==1.78

networkx==2.4

Results and Outputs
Comprehensive analysis of 10 major MTB virulence factors

Drug resistance prediction model with 85% accuracy

Mutation frequency analysis across geographical regions

Virulence factor interaction networks

Statistical correlation matrices

Publication-ready visualizations and charts

Applications and Implications
Early detection of drug-resistant TB strains

Personalized treatment planning based on virulence profiles

Vaccine development targeting specific virulence factors

Public health surveillance of emerging resistant strains

Diagnostic tool development for clinical settings

References
Virulence Factor Database (VFDB): http://www.mgc.ac.cn/VFs/main.htm

TB Drug Resistance Mutation Database (TBDReaMDB): https://tbdreamdb.ki.se/Info/

PHIDIAS Pathogen-Host Interaction Database: http://www.phidias.us/index.php

Victors Virulence Factor Database: http://www.phidias.us/victors/index.php

NCBI Mycobacterium tuberculosis Genome Data: https://www.ncbi.nlm.nih.gov/

WHO Global Tuberculosis Report 2019

Future Work
Integration of transcriptomic data for comprehensive analysis

Development of web-based prediction tool for clinical use

Expansion to include more MTB lineages and rare mutations

Incorporation of structural biology data for mechanistic insights

Real-time monitoring of emerging resistance patterns

Academic Context
This project was submitted as partial fulfillment of the Bachelor of Technology degree in Computer Science and Engineering with specialization in Bioinformatics at VIT University. The work represents a comprehensive integration of computational methods with biological domain knowledge to address a significant public health challenge.




