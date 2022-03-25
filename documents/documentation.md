![autoMLfast_logo_small](https://user-images.githubusercontent.com/32124230/160170864-de75e2b0-b587-425a-92c2-779460be097b.png)
  
Developed by [**Peter Skelsey**](mailto:peter.skelsey@hutton.ac.uk?subject=findOUT), James Hutton Institute, Dundee

# USER GUIDE

## Table of Contents
* [Background](#background)
* [Basic operation](#basic-operation)
* [Methods](#methods)

  
  
## Background
The app uses unsupervised anomaly detection algorithms to determine a decision boundary separating outliers and inliers in your data. Any future instances that fall inside the decision boundary will trigger a risk alert. See the reference at the bottom of the [README](https://github.com/pskelsey/findOUT/blob/master/README.md) for mathematical details on each algorithm.

## Basic operation
*Buttons*: Click the button.  
*Check-boxes*: Check the box.  
*Switches*: Drag the circluar switch to the left or right.  
*Knobs*: Drag the control around to your selection, or click on your selection.  
*Numeric fields*: Click in the white box to change the numerical value. Then hit enter or click outside the box.  

Note: Certain options may be 'greyed out' and unavailable to ensure conflicting choices are not made, e.g., you cannot hit the Run button until you have used the Load button to upload your data.

## Methods
Your data must be stored in an excel file (.xls or .xlsx). You need two predictor variables with an equal number of values. These are stored in a separate worksheet in your excel file. Name the worksheets 'var1' and 'var2'. In each worksheet, data corresponding to different events / objects should be stored in rows, and measurements corresponding to the same event should be stored in columns. For example, if you have data on 5000 events and for each event you have 10 measurements of predictor variable A and predictor variable B, then worksheets var1 and var2 will both contain a 5000 x 10 matrix of numbers. Missing data must be entered as 'NaN' (without the quotes) or left as an empty cell. There should be no text entries anywhere in your excel file, i.e., no headers and no text entires for missing data. You can, however, use 'Inf' (without the quotes) to represent infinity. If your file does not meet these requirements then a warning will occur when you try to upload it. An example dataset ('exampleWeatherData.txt') has been provided to help you get you up and running. This contains synthetic data for 200 crop disease outbreaks, where the two predictor variables are: (1) the number of hours of relative humidity >90% per day, and (2) the daily minimum temperature. The data span a 28-day period prior to the date each outbreak was reported, and are used to relate weather conditions for infection to the dates at which disease was observed in the crop. Each worksheet in the example datafile therefore contains a 200 x 28 matrix of numbers. 
