# Senior_Coordinator_Data_and_GIS_Analytics
This repository implements a complete, reproducible geospatial analytics workflow for a senior technical assessment in Data &amp; GIS Analytics. It includes R pipeline, environment lockfile, structured configuration, and a Quarto book that documents analytical decisions, assumptions, limitations, and decision‑grade outputs for public health contexts.

This repository uses Git LFS for large files (GeoPackages, TIFFs, models).
Install Git LFS before cloning:

    git lfs install

# README — Guide to the Worked Assessment
This folder contains all the materials used to complete the worked assessment. The structure reflects the full analytical workflow: from raw data engineering, through quality assurance, to final statistical analysis and mapping.

1. Python Notebooks (Notebook1, Notebook2, Notebook3)
These notebooks form the backbone of the technical workflow. They contain:

Data engineering — ingestion, cleaning, harmonisation of raw datasets

Quality assurance — validation rules, integrity checks, and reproducibility safeguards

Processing pipelines — step‑by‑step transformations used to prepare the data for analysis

This is the “hardcore” part of the workflow: everything that ensures the data is trustworthy before any analysis or mapping is attempted.

2. R Documentation (Books Folder)
The books folder contains the full R‑based analytical and mapping workflow, including:

* Statistical analysis

* Spatial modelling

* Mapping and visualisation

Where the Python notebooks focus on engineering and QA, the R documentation focuses on interpretation, analysis, and cartographic outputs.

3. How to Use This Repository
To understand the full workflow:

Start with the Python notebooks  
They show how raw data becomes clean, validated, and analysis‑ready.

Move to the R documentation  
This is where the cleaned data is analysed, modelled, and mapped.

Use both together  
The assessment is designed as a two‑language workflow:

Python for engineering and QA

R for analysis and mapping

This separation keeps the workflow reproducible, transparent, and easy to audit.

4. Why This Structure Matters
This structure reflects best practice in modern data work:

Clear separation of engineering and analysis

Reproducible pipelines

Transparent documentation

Modular workflows that can be reused or extended

It also aligns with the principles of data governance, accountability, and reproducibility expected in professional geospatial and public‑health analytics.