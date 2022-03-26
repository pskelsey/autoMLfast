![autoMLfast_logo_small](https://user-images.githubusercontent.com/32124230/160239038-1f3d9f56-7974-4ffa-9221-59dd458de6aa.png)

Developed by [**Peter Skelsey**](mailto:peter.skelsey@hutton.ac.uk?subject=findOUT), James Hutton Institute, Dundee

## Basic overview
A standalone desktop app that automates the machine learning workflow to generate the best predictive model for your data. 
* Upload your own data or use our example data (ionosphere.csv) to get started.
* autoMLfast automatically cleans and preprocesses your data so it is ready for learning.
* Choose how many models you want to produce.
* autoMLfast tries an appropriate subset (depending on your data) of the following models for regression tasks:  
  - Gaussian process regression models, Kernel regression models, Linear regression models, neural networks, Support vector machines, binary decision regression trees, and various Ensemble regression models.
* autoMLfast tries an appropriate subset of the following models for classification tasks:
  - Discriminant analysis classifiers, Kernel classification models, k-nearest neighbor models, Linear classification models, Naive Bayes classifiers, Neural network classifiers, Support vector machines, binary decision classification trees, and various Ensemble classification models.
* These are *simultaneously* trained and tuned using holdout and *k*-fold cross-validation procedures with either random search, Bayesian or ASHA optimization.
* The most successful model is automatically selected and can be used to make predictions on new data.
* The process is repeated until you have the number of models you requested.
* Use the best model to make predictions on new data.
* Save your results.
* autoMLfast runs computations in parallel on your computer's processors and is fast and user-friendly. 
 
### Rationale
The app is intended for users with no or limited modelling or machine learning experience, and provides a front-end to some state-of-the-art machine learning algorithms and techniques. Experienced machine learning practitioners  

### Installation and loading
The app is freely available to download and install on any dekstop PC. To download the app click the green "Code" button and select 'download ZIP' from the dropdown menu. The executable file 'autoMLfast.exe' is a web-based installer (you will need an internet connection) that will install the app and download 'MATLAB Runtime' to your computer. MATLAB Runtime is a completely free execution engine that enables you to run MATLAB applications on computers that do not have a MATLAB license. New features will be added progessively to the app, so to check for a new release click on the 'release' button near the top of the page.

NOTE: When the app is loading the splash screen may disappear for a brief interval before the app opens - there is no need to try and load it again, just give it a few seconds. The GUI is 'responsive' and can be scaled to any size, however this will change the layout of the controls. 

### Documentation
A guide on how to use the app is provided in the [Documentation](https://github.com/pskelsey/autoMLfast/blob/master/documents/documentation.md). This also contains some methodological detail for the purposes of reporting results. 

### License
The MIT License (MIT) 2022 - Peter Skelsey. For more details, please have a look at the [LICENSE](https://github.com/pskelsey/autoMLfast/blob/main/LICENSE).
