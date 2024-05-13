# PSS3E9
Playground Kaggle Competition - PSS3E9

This [playground competition](https://www.kaggle.com/competitions/playground-series-s3e9/overview) is about **predicting the strength of the concrete** based on the different features provided in the dataset.

The dataset can be obtain using Kaggle API (`kaggle competitions download -c playground-series-s3e9`). As all the playground competitions the dataset has been generated synthetically. This is done in order to have a variaty of real dataset to practice and ensure test labels are not publicy available.

The real data set can be found at Kaggle datasets: [Concrete Strength Prediction](https://www.kaggle.com/datasets/mchilamwar/predict-concrete-strength) and it can be downloaded using the Kaggle API (`kaggle datasets download -d mchilamwar/predict-concrete-strength`).

#### Evaluation metric

The evaluation metric for this competition is the **Root Mean Squared Error (RMSE)**. 

$$\mathrm{RMSE} = \sqrt{\frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2}$$

#### Submision file:

The Submission file must have the following format:
````csv
id,Strength
5439,55.2
5440,12.3
5441,83.4
etc.
````


### Feature description:

| Feature | Description |
| -------- | ----------- |
| CementComponent | Amount of cement mixed |
| BlastFurnaceSlag | Amount of Blast Furnace Slag mixed |
| FlyAshComponent | Amount of Fly Ash mixed |
| WaterComponent | Amount of water mixed |
| SuperplasticizerComponent | Amount of superplasticizer mixed |
| CoarseAggregateComponent | Amount of coarse aggregate mixed |
| FineAggregateComponent | Amount of fine aggregate mixed |
| AgeInDays | Number of days the concrete was left to dry |
| Strength | Final strength of the concrete (Target) |
