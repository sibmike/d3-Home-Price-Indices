# Visualizing Accurate Home Price Indices with kepler.gl

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
