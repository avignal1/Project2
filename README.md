# Project 2

## Modeling

### Preparation

- Songs created before 1960 had very low popularity score so removed from dataset

![RemoveSongsBefore1960](Resources/images/RemoveSongsBefore1960.PNG)
- Only columns which clearly respresnted the songs were used

![UseOnlyEssentialColumns](Resources/images/UseOnlyEssentialColumns.PNG)
- We splited data into 14 input X values to predict 1 output y value

![SplitDataIntoXandY](Resources/images/SplitDataIntoXandY.PNG)
- Used Standard scaler to scale and transfrom X

![StandardScaler](Resources/images/StandardScaler.PNG)

### Process

- Initailized Neural Networks with 4 hidden layes

![InitalizeNueralNetworks](Resources/images/InitalizeNueralNetworks.PNG)
- Compiled & Fitted Model

![CompileAndFit](Resources/images/CompileAndFit.PNG)

### Analyze
- Model statistic shows a p-value less that 0.05

![Statistics](Resources/images/Statistics.PNG)
- Plot show loss getting lesser in Trainning

![LossFunctionPlot](Resources/images/LossFunctionPlot.png)
- Plot show loss between Training & Testing

![TrainvsTest](Resources/images/TrainvsTest.png)
- Actual popularity vs Predited popularity from model is closer

![ActualvsPredition](Resources/images/ActualvsPredition.PNG)

### Model Comparison - Classification Types
- Ran our test/train data for four classification type models:
    1. Deep Learning
    2. Gradient Boosting
    3. Decision Trees
    4. Random Forest

- Ran summary statistics to receive an accuracy score for each model

![ModelComparison](Resources/images/Model_Comparison.png)
- Most accurate model was Random Forest

### Model Comparison - Scaler Types
- Similarly to the step above, ran our test/train data for four Scaler Types:
    1. MinMax
    2. Standard
    3. RobustScaler
    4. QuantileTransformer

- Ran summary statistics to receive an accuracy score for each scaler

![ScalerComparison](Resources/images/ScalerComparison.png)
- Most accurate model was StandardScaler
