# deep_learning_wk14
Homework Due 11.8.2019

I didn't find the FNG Index to be any kind of predictor for future prices.

Model 1:

    10 Day Window
    10 Nodes Each Layer
    50 Epochs

![Closing Prices](Images\model_1_eval_close.PNG)
![FNG Index](Images\model_1_eval_fng.PNG)

Closing Prices vs FNG Index

![](Images\model_1_plot_close.png) ![](Images\model_1_plot_fng.png)

Model 2:

    1 Day Window
    10 Nodes Each Layer
    50 Epochs

Using a 1 Day window got the best results with Closing price data.

![](Images\model_2_eval_close.PNG)
![](Images\model_2_eval_fng.PNG)

![](Images\model_2_plot_close.png)
![](Images\model_2_plot_fng.png)

Model 3:

    5 Day Window
    30 Nodes Each Layer
    50 Epochs

Despite more nodes, and longer window, this model did not do as well as Model 2 for Closing Prices.

![](Images\model_3_eval_close.PNG)
![](Images\model_3_eval_fng.PNG)

![](Images\model_3_plot_close.png)
![](Images\model_3_plot_fng.png)

