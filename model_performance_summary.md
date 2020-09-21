## Model Performance Summary

Based on multiple scenerios the model with the lower loss performance was the LSTM Closing Prices Stock Predictor.  It achieved a loss of 0.002374 compared to the LSTM FNG Stock Predictor that acheived a 0.0734.  With that said, neither model was accurate at predicting the real values. 

The closing price model worked best with a window size of 1 while the FNG model worked better with a window size of 10

The Closing Price model tracks the actual values better over time as seen by the plots below.

![closing_price_plot.jpg](Images/closing_price_plot.jpg)

![fng_plot.jpg](Images/fng_plot.jpg)