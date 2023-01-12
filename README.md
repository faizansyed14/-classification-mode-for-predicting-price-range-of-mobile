#predicting-price-range-of-mobile
Create a classification model to predict whether price range of mobile  based on certain specifications
Dataset as 21 features and 2000 entries. The meanings of the features are given below.
1) battery_power: Total energy a battery can store in one time measured in mAh
2) blue: Has bluetooth or not
3) clock_speed: speed at which microprocessor executes instructions
4) dual_sim: Has dual sim support or not
5) fc: Front Camera mega pixels
6) four_g: Has 4G or not
7) int_memory: Internal Memory in Gigabytes
8) m_dep: Mobile Depth in cm
9) mobile_wt: Weight of mobile phone
10) n_cores: Number of cores of processor
11) pc: Primary Camera mega pixels
12) px_height: Pixel Resolution Height
13) px_width: Pixel Resolution Width
14) ram: Random Access Memory in Mega Bytes
15) sc_h: Screen Height of mobile in cm
16) sc_w: Screen Width of mobile in cm
17) talk_time: longest time that a single battery charge will last when you are
18) three_g: Has 3G or not
19) touch_screen: Has touch screen or not
20) wifi: Has wifi or not
21) price_range: This is the target variable with value of 0(low cost), 1(medium cost), 
2(high cost) and 3(very high cost).
Steps to consider:
1)Remove handle null values (if any).
2)Split data into training and test data.
3)Apply the following models on the training dataset and generate the predicted value for 
the test dataset
a) Logistic Regression 
b) KNN Classification
c) SVM Classifier with linear and rbf kernel
d) Decision Tree Classifier
e) Random Forest Classifier
4)Predict the price range for test data
5)Compute Confusion matrix and classification report for each of these models.
6)Report the model with the best accuracy
