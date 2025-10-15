# Frailty Detection and Management: Enhancing Interventions with Interpretable Machine Learning

**`PRESENTED AT:`** GQP Poster Event, Worcester Polytechnic Institute (WPI)  
**`LOCATION:`** Worcester, MA  
**`DATE:`** April 25, 2025  
**`TYPE:`** Graduate Capstone (GQP) Poster Presentation  

## Authors  
Dalton Macres, Sreeram Marimuthu, Sheroz Shaikh, Madelyn Marcotte, Aayush Sangani  
**Advisors:** Prof. Chun-Kit Ngan, Prof. Fatemeh Emdad  
**Sponsors:** Dr. Paulo Pinho, Jacob Dodd  

## Abstract  

Frailty represents a significant vulnerability for older adults, impacting activities of daily living and increasing risk for disability, hospitalization, and mortality. With a growing aging population, it is critical to develop scalable, interpretable machine learning models to detect frailty onset and progression, inform timely interventions, and reduce long-term social and economic burdens.

This project focused on developing and evaluating ML models for early frailty detection, phenotype progression modeling, and mortality risk prediction. Using claims, clinical, survey, demographic data with ICD-10 and HCC codes, we engineered features based on the Kim et al. frailty index and custom indicators. 

Key model types included traditional ML models, the AutoML or Automated Machine Learning and Cox proportional hazards for time-to-event prediction. Evaluation metrics such as RMSE, R², C-index and AUC demonstrated strong predictive performance. Interpretability techniques like calibration curves, feature importance rankings, and ROC/PR curves were used to ensure clinical insight and model transparency.

This work supports informed, data-driven frailty management strategies, helping clinicians identify at-risk patients and deliver timely, targeted care.

## My Contribution  

I led the machine learning implementation and experimentation for this project on 2 main areas - Frailty Detection and Phenotype Modeling. 

This included:
- Designing and running 10 ML experiments for frailty detection (3 on Kim CFI forecasting, 7 on Phenotype Modeling of 53 indicators) over multiple patient strata.      
- Achieving strong performance (RMSE: 0.0052, R²: 0.9956, AUC: up to 0.98).   
- Visualizing model behavior with calibration curves, ROC/PR curves, and feature importance plots.   
- Training and deploying a total of 389 models to production.    

## Status Update  
This work was completed as part of WPI’s Graduate Qualifying Project (GQP) in Fall '24. A summary poster is included in this repo. Further dissemination is under consideration.

