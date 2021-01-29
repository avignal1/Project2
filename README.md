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

![LossFunctionPlot](Resources/images/LossFunctionPlot.PNG)
- Plot show loss between Training & Testing

![TrainvsTest](Resources/images/TrainvsTest.PNG)
- Actual popularity vs Predited popularity from model is closer

![ActualvsPredition](Resources/images/ActualvsPredition.PNG)
