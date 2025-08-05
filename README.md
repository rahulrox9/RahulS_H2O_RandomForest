# H2O_RandomForest
H₂O Prediction in Icelandic Melts Using Random Forest Regression <br>
This notebook trains Random Forest models on seven oxide compositions (SiO₂, Al₂O₃, FeO, MgO, CaO, Na₂O, K₂O) of plagioclase-hosted, olivine-hosted and clinopyroxene-hosted melt inclusions to estimate H₂O content in volcanic glass samples and melt inclusions.

Author: Rahul Subbaraman <br>
Affiliation: University of Manchester <br>
Email: rahul.subbaraman@manchester.ac.uk <br>
Date: 05-08-2025

## How to use

1. Install dependencies: pip install -r requirements.txt
2. Open the Jupyter Notebook: jupyter notebook H2O_RF_predictor.ipynb
3. Run all cells sequentially.

## Data
Place your training and testing CSV files inside the Imports/ folder.

IMPORTANT: Update the file names in the Imports & Setup code cell in the notebook to match your filenames.

Example sample datasets provided:
- `Sample_Train_data.csv`
- `Sample_Test_data.csv`

## Outputs
Results and trained model will be saved in the `Exports/` folder.
