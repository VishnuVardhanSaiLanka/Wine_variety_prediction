# Wine_variety_prediction
Part-1:

DATA PRE-PROCESSING AND VISUALIZATION: 
 1. Given datasets are closely observed and the missing values are cleaned.
 2. Data is visualized using matplotlib and seaborn libraries.
 3. Following observations are made by interpreting the visualization of data:
     - California was the most reviewed province
     - Most expensive wine is Bordeaux-style Red Blend with USD 3300
     - Cheapest wines are available at USD 4
     - Wines in the 10.00 - 20.00 range have frequently better ratings.The reason could be that most people save expensive wine        for occasions and use cheap wine more frequently. Wine Sellers can focus on this range to increase their profits.
     - There is no correlation between price and points(quality) in most cases.


Part -2:

MODEL TRAINING AND PREDICTION:
 1. The variety of wine is predicted based on the 'review_description' feature.
 2. Using NLTK library the text is vectorized.
 3. This vectorized text is fed as an input to the neural network and output is the multi-class 'variety' of wine (using label     encoding). 
 4. The neural network used is 100 layers dense, has relu activation function for input, hidden layers and Softmax activation       for output layer. It uses Adam's optimizer.
 5. The model shows an accuracy of 80.2 % on training set.
 6. The predicted values of test data are fed into a csv file along with all other features.
