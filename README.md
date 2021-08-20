# A game theory approach to explain HSI

This repository contains the code for the implementation of the paper 'A Novel Approach to Identify the Spectral Bands that Predict Moisture Content in Canola and Wheat', accepted for publishing in "Biosystems Engineering" Journal. This work was supported in part by an AI for Earth Microsoft Azure Compute Grant.

Due to the relevance of agriculture in economy and human development, the inclusion of technology in this activity is of utmost importance. Our paper
presents two main contributions: (i) an accurate DL model for the prediction of the moisture content of canola and wheat crops, based on HSI taken by a number of UAV flights; and (ii) a novel approach for assessing the importance of spectral bands in those predictions, using a game-theory model-interpretability analysis that was used as a tool for supervised band selection. 

The DL model for moisture content prediction included a final ensemble of two branches for analysis of spatial and spectral features, and it reached a coefficient of determination of 0.916 and 0.818 for the canola and wheat test datasets, respectively. 

![Block diagram that represents the whole information extraction scheme and analysis of predictions](https://github.com/juliotorrest/game_theory_HSI/blob/main/block.png)

The SHAP analysis that allowed us to study the individual predictions of the models, and this is one of the most important contributions of this paper because this approach could eventually lead to the design and implementation of more tailored software and hardware for the analysis of spectral information.

In this repository we have included the SHAP analysis, based on the models that we trained.
