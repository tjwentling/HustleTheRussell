# HustleTheRussell

The Russell US Indexes, from mega cap to microcap, serve as leading benchmarks for institutional investors. The modular index construction allows investors to track current and historical market performance by specific market segment (large/mid/small/micro cap) or investment style (growth/value/defensive/dynamic). All sub-indexes roll up to the Russell 3000® Index. The Russell US Indexes can be used as performance benchmarks, or as the basis for index-linked products including index tracking funds, derivatives, and Exchange Traded Funds (ETFs).

In HussleTheRussell, we are analyzing the top 7 Russell indexes to determine how our models will perform compared to their perspective index. We have pulled data from Alpaca to get baseline data which we have used to model, test, and predict future returns. The following is what we discovered.

# Dates

Start Date of Training Data: 2018-01-01

Start Date of Prediction Data: 10/31/2022

End Date of Prediction Data: 6/30/2023

# Indices

![](figures/image.png)

# Summary

Our analysis attemps to predict future performance of various equity market stylistic factors by analyzing historical return profiles of 7 Russell ETFs that comprise the entire spectrum of the US equity market. This analysis will also incorporate macroeconomic data points that will help us describe results and potential deviations in predicted relative returns. 

Tools:
* Alpaca
* Jupyter Lab
* Pandas
* Sklearn
* keras
* hv.plot
* macroeconomic data (gov sites)


![image](https://github.com/tjwentling/HustleTheRussell/assets/57773931/f601c6f7-a9c1-422e-8063-f6174c73d241)

# IWV
# IWB
# IWF
# IWD
# IWM
# IWO
# IWN

# References only:

Create a Jupyter Notebook, Google Colab Notebook, or Amazon SageMaker Notebook to prepare a training and testing dataset.


 Optionally, apply a dimensionality reduction technique to reduce the input features, or perform feature engineering to generate new features to train the model.


 Create one or more machine learning models.


 Fit the model(s) to the training data.


 Evaluate the trained model(s) using testing data. Include any calculations, metrics, or visualizations needed to evaluate the performance.


 Show the predictions using a sample of new data. Compare the predictions if more than one model is used.


 Save PNG images of your visualizations to distribute to the class and instructional team and for inclusion in your presentation and your repo's README.md file.


 Use one new machine learning library, machine learning model, or evaluation metric that hasn't been covered in class.


 Create a README.md in your repo with a write-up summarizing your project. Be sure to include any usage instructions to set up and use the model.
