# real estate dz 
This repository contains the final project of the MLOps Zoomcamp 2023, offered by DataTalksClub (https://datatalks.club). You can explore the project's structural design by following this <a href="docs/project_schema.png">link</a>.

The project consist on scraping real estate data from [Ouedkniss](https://www.ouedkniss.com/) in order to create a price estimating ML modele. To this end we used:
- Postgres in order to save data in databases
- Prefect as an orchestrator software
- MlFlow for experiment tracking
- XgBoost as a machine learning model
- Evidently in order to monitor the performance of the best Xgboost model
  
