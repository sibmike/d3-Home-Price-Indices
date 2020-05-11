# Visualizing Accurate Home Price Indices with kepler.gl

Google Slides [Presentation](https://docs.google.com/presentation/d/1v552gDNZSte5xmnbQpCn0ktDhPVEksXztkyXCSqh8IY/edit?usp=sharing) of the research project

### Video Presentation of the project.
[Link](https://drive.google.com/file/d/1weXCMnTCco9CEKAKLE2nrCHK9sfJBou0/view)

### Address Merging-Assess
Normalize addresses in Assessor's dataset and merge it with enterprise address database for SF.
pandas, regex, fuzzywuzzy algorithm based on Levenshtein Distance to calculate the differences between sequences

### Address Merging-Sales
Normalize addresses in Assessor's dataset and merge it with enterprise address database for SF.
pandas, regex, fuzzywuzzy algorithm based on Levenshtein Distance to calculate the differences between sequences

### Training
Use geotagged sales dataset to train LGBM model to predict home prices in SF (MAPE ~10%)
Use asessors dataset to predict home prices for every home in SF on mnothly basis for 1993-2020 time window.
Calculate monthly percentage price difference for every home in SF to create interactive visualization of accurate price index.

### Sampling
Use 5% random sample with replacement to upload to kepler.gl

### Datasets
[Enterprise Addresses](https://drive.google.com/open?id=1guHxmJz7hNUiOPdfE1Ex_ENjkX0wbdZR)

[Assessors Data](https://drive.google.com/open?id=12sheEc2WyE7j6GKqcfLHlAsiBYwr88nP) 

[Kepler dataset](https://drive.google.com/open?id=10qNKyUdcOY9CYPS10loDG337iJZx50u1) 

### Intercative HTMLs 
[SF Home Prices](https://drive.google.com/open?id=1QxJn_AcntnR-ndeg8RkzkQznZvXtGYYA) - View. Kepler.gl map without filters.

[SF Home Prices](https://drive.google.com/open?id=1X_8_Ss3eGsLnWXqs-OH6AzVfNfCE_iQZ) - Filtered. Kepler.gl editable map with filters.
