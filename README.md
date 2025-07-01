# Interfacial Tension Prediction in Quaternary Hydrogen Systems

This repository contains models for predicting interfacial tension (IFT) in quaternary gas–brine systems comprising hydrogen, methane, nitrogen, and brine. 

The approach combines decision tree-based ensemble learning methods with Bayesian hyperparameter optimization to produce accurate predictions. 

## a. Objective

The main goal of this work is to develop a reliable and data-driven framework for predicting IFT under varying reservoir conditions. The model aids in understanding how cushion gas composition, salinity, and reservoir conditions impact IFT behavior, which in turn influences capillary entry pressure, storage height, and storage safety.

## b. Methods Used

- **Baseline Model:** Decision Tree Regressor (DT)
- **Ensemble Models:**
  - Random Forest (RF)
  - Extremely Randomized Trees (Extra Trees)
  - Gradient Boosting Regression (GBR)
  - Light Gradient Boosting Machine (LGBM)

- **Hyperparameter Optimization:**
  - Bayesian Optimization

- **Model Evaluation:**
  - Coefficient of determination (R2)
  - Root mean square error (RMSE)
  - Mean absolute error (MAE)
  - Average absolute percentage relative error (AAPRE)

- **Interpretability:**
  - Permutation Feature Importance
 
## Reference

For detailed methodology, benchmarking results, and practical applications of the models, please refer to:

  - Link to the paper will be added later.
