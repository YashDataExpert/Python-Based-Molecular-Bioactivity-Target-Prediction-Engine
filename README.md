Key Functional Modules 
Molecular Data Parsing: Efficiently processing large-scale .csv and .sdf datasets containing chemical information.
Feature Engineering (Fingerprinting): Converting chemical SMILES strings into numerical vectors (Morgan Fingerprints) for machine learning compatibility.
Bioactivity Regression Model: A Scikit-Learn based ensemble model to predict $pIC_{50}$ values (the standard measure of drug potency).
Virtual Screening Pipeline: An automated script to "screen" thousands of molecules against a specific protein target to find the "Top 10" lead candidates.
Data Visualization: Custom Plotly and Matplotlib dashboards to visualize Chemical Space (PCA/t-SNE) and Structure-Activity Relationships (SAR).
Core Python Libraries Used:Pandas & NumPy: For high-performance data manipulation.Scikit-Learn: For predictive modeling and statistical validation.
Matplotlib/Seaborn: For biological data visualization.
RDKit (Python Library): The industry-standard library for handling chemical structures and molecular descriptors.
