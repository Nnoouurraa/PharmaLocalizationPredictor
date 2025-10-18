Strategic Analysis of KSA's Drug Market & Localization Blueprint
This project performs a comprehensive analysis of Saudi Arabia's registered human drug market (2025 data, Local and Imported) to guide national self-sufficiency goals.

Key Project Goals
Quantify Market Dependency: Assess the reliance on imports (71% vs. 29% local).
Identify Critical Gaps: Pinpoint strategic weaknesses in advanced manufacturing (NCE and Biologics).
Predict Readiness: Build a predictive model to define the specific product characteristics that signal a local manufacturer's readiness for high-tech production.

Core Findings
The predictive model successfully identifies factors driving technological capacity:

Insight	Result	Strategic Value
Localization Driver	82% of the model's prediction relies on SizeUnit_l/ml (complex liquid dosage forms).	Directs investment toward existing local factories that already have expertise in sterile liquid production.
Model Reliability	72% Precision for predicting Advanced Producers.	Provides a reliable tool for filtering and selecting partners for NCE/Biologics technology transfer.
Methodology

The project uses an integrated approach:
Data: Cleansed and merged Local and Imported drug registration data.
Model: Decision Tree Classifier with Class Weighting (to overcome data imbalance) to predict manufacturer readiness.

How to Run
Ensure CSV files (Human Drugs Products Local.csv, Imported human drug products) are in the content folder.
Run the main script: python SFDA2025-2.py
