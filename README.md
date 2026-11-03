# Mapping suspended particulate matter on the Belgian coast

- `Coastal_final_method.ipynb`: final Sentinel-2 and Sentinel-3 red/green models,
  reserved-date evaluation, and mapping code.
- `Coastal_model_training.ipynb`: exploratory analysis and model comparisons.

Start Jupyter in this folder. To reproduce the final fit and evaluation, skip
the opening A2 image cell, then run Sections 1–4 of the final notebook. The
mapping cells and some experiments need external inputs that are not included.
This repository does not reproduce satellite acquisition or preprocessing.

The bundled tables are processed satellite–field matchups, fixed splits, and
small result tables. Local file-path columns were removed from the matchup
table. Notebook outputs were cleared.

## Data sources

- [LifeWatch / VLIZ](https://doi.org/10.14284/652), CC BY 4.0.
- [SOMLIT-Wimereux / Breton et al.](https://doi.org/10.17882/96639), CC BY-SA 4.0.
  Adapted SOMLIT data are shared under the same licence.
- [Rijkswaterstaat Waterdata](https://rijkswaterstaatdata.nl/waterdata/).
- Satellite reflectance was derived from Copernicus Sentinel-2 and Sentinel-3 data.
