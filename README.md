# Speed-Dating-Prediction

## 

This is the weekly coding challenge posted on Siraj Raval's youtube channel. The [dataset](https://www.kaggle.com/annavictoria/speed-dating-experiment) can be found on kaggle. This model is built to predict whether or not someone will be matched. 

## EDA 

After finding a data dictionary for this dataset, I was able to do some much deeper data exploration. To start it is important to note that there is a class imbalancement between 'match' & 'no match' labels. 

<img src="https://raw.githubusercontent.com/VinceKumar/Speed-Dating-Prediction/master/img/Match%20Distribution.png" width="400"> 

There is ~5:1 ratio therefore I ignored Accuracy as a metric and optimized Precision and Recall as the metrics.



## Models

### Random Forest
   ```
   Accuracy Score: 0.88
   Precision Score: 0.98
   Recall Score: 0.20
   ```

 
## Dependencies:
 - Numpy
 - Pandas
 - Matplotlib
 - Seaborn
 - Sklearn
 - Tensorflow 
 



