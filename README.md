# Mapping turbidity on the Belgian coast

- `Coastal_final_method.ipynb`: final polished Sentinel-2 and Sentinel-3 red/green model pipeline,
   evaluation, and mapping code.
- `Coastal_model_training.ipynb`: messy, exploratory analysis and model comparisons.

Start Jupyter in this folder. To reproduce the final fit and evaluation, skip
the opening A2 image cell, then run Sections 1–4 of the final notebook. The
mapping cells and some select experiments need external inputs that are not included here.
The code in this repository does not redo the satellite acquisitions or preprocessing.

The given tables are processed satellite–field matchups, fixed train-test splits, and
small result tables.

## Main data sources

- [LifeWatch / VLIZ](https://doi.org/10.14284/652), CC BY 4.0.
- [SOMLIT-Wimereux / Breton et al.](https://doi.org/10.17882/96639), CC BY-SA 4.0.
  Adapted SOMLIT data are shared under the same licence.
- [Rijkswaterstaat Waterdata](https://rijkswaterstaatdata.nl/waterdata/).
- Satellite reflectance was derived from Copernicus Sentinel-2 and Sentinel-3 data.

# Authors
Arda Baysal, Emil Holub, Bagad Tikkavat
