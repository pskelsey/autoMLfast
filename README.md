![autoMLfast_logo_small](https://user-images.githubusercontent.com/32124230/160170864-de75e2b0-b587-425a-92c2-779460be097b.png)

Developed by [**Peter Skelsey**](mailto:peter.skelsey@hutton.ac.uk?subject=findOUT), James Hutton Institute, Dundee

## Basic overview
A standalone desktop app that automates the machine learning workflow to generate the best predictive model for your data, all with the click of a few butons! It's ideal for complete beginners to machine learning, or for anyone who wants fast, accurate results.
* Upload your own data or use our example data (ionosphere.csv) to get started.
* autoMLfast automatically cleans and preprocesses your data so it is ready for learning.
* Choose how many models you want to produce.
* autoMLfast tries an appropriate subset (depending on your data) of the following models for regression tasks:  
  - Gaussian process, kernel, linear, neural network and support vector machine regression models, various ensemble regression models, and binary decision regression trees.
* autoMLfast tries an appropriate subset of the following models for classification tasks:
  - disciminant analysis, kernel, linear, naive bayes, neural network, binary decision, and support vector machine classifiers, various ensemble classifiers, and *k*-nearest neighbor models
* These are *simultaneously* trained and tuned using holdout and *k*-fold cross-validation procedures with either random search, Bayesian or ASHA optimization.
* The most successful model is automatically selected and can be used to make predictions on new data.
* The process is repeated until you have the number of models you requested.
* Use the best model to make predictions on new data.
* Save your results.
* autoMLfast runs computations in parallel on your computer's processors and is fast and user-friendly. 


### Installation and loading
The app is freely available to download and install on any dekstop PC. To download the app click the green "Code" button and select 'download ZIP' from the dropdown menu. The zipped executable file 'autoMLfast.exe' is a web-based installer (you will need an internet connection) that will install the app and download 'MATLAB Runtime' to your computer. MATLAB Runtime is a completely free execution engine that enables you to run MATLAB applications on computers that do not have a MATLAB license. So not only will you get this app, you will have access to thousands of others! To check for a new release of this app, click on the 'release' button near the top of the page.

NOTE: When the app is loading the splash screen may disappear for a brief interval before the app opens - there is no need to try and load it again, just give it a few seconds. The GUI is 'responsive' and can be scaled to any size, however this will change the layout of the controls. 

### Documentation
A full guide on how to use the app is provided in the [Documentation](https://github.com/pskelsey/autoMLfast/blob/master/documents/documentation.md)

### License
The MIT License (MIT) 2022 - Peter Skelsey. For more details, please have a look at the [LICENSE](https://github.com/pskelsey/autoMLfast/blob/main/LICENSE).
