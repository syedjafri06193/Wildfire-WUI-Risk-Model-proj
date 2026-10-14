# Wildfire-WUI-Risk-Model-proj

Wildfire risk at the wildland-urban interface. Build a fire risk model using fuel data (LANDFIRE), topography, historical fire perimeters (MTBS/CAL FIRE), and building footprints. Then test how well your model would have predicted structure losses in a recent fire. Methods: machine learning (random forest, XGBoost) on spatial features, with careful spatial cross-validation to avoid autocorrelation leakage. Contribution: the validation against real loss data, and explaining which variables matter most.
