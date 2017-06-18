# Modelling the AllState Claim Severity Dataset (2017)
### by Jérôme E. Blanchet, Senior Analyst | Data Scientist 

981 Gulf Pl, Ottawa, ON K1K 3X9 (613) 746-4120 
Jeromeblanchetmodelling@gmail.com

  
  
# Abstract

This paper is about building predictive modelling with the Allstate Claim Severity Dataset. This is a work in progress. All sections are unfinished and make progress every day. The dataset include 72 binary variables, around 45 categorical variable with more than 2 categories and 15 continuous variables. All data are perfecly anonymous. We don't know what the data represent. The Target variable is continuous and represent the claim severity. 

Besides showing that innovative algorithms can out-perform more traditional tools, the goal of this paper is mainly about designing creative way to show several information on a single and simple graph. For example, presenting the structure of the full dataset on a single graph or showing the behavior of all trees made of a random forest on a single chart. The objective is also to show that advanced algorithms such as Neural Hyperparameters optimization is not a blackbox process, but rather an intuitive and interpretable journey of discovery. 

Right now, <font color=blue>Keras (with tensorflow or Theano backend)</font> is probably the most popular library for deep learning and Neural Network design. It allow you to do fast prototyping of your ideas and built a final product quickly. In the other hand, building a neural network from scratch directly with <font color=blue>Tensorflow, Theano or Numpy</font> has its own advantages. It will allow you to see the low level process with every single iteration. This way of doing things is important, especially if you want to convince a manager about the 'No Blackbox' status of an algorithm. This way of doing things can contribute to accelarate the Technology Transformation process within a Company. It is one thing to own the technical knowledge, it is something else to present an algorithm and succeed to show that it is interpretable, intuitive and able you to replicate results.  

This paper use an academic way of showing results. In the other hand, the ultimate goal of this paper is to convince is audiences that you can extract business value with innovative algorithms and create a simple and concret final product out of it.

# Table of Contents

Part 1) Data and Modules Importation....................................................................................................XXX  
Part 2) Data Description and Interaction ....................................................................................................XXX
 
Part 3) Preprocessing the Data...............................................................................................XXX  
 
-  3.0 Logarithmic Tranformation 
-  3.1 Dimensionality Reduction with Principal Component Analysis (PCA) Binary Variables Only  
-  3.2 Dimensionality Reduction with T-distributed stochastic neighbor embedding (t-SNE) on top (PCA)  
-  3.3 Dimensionality Reduction with Principal Component Analysis (PCA) Continuous Variables Only  
-  3.4 Dimensionality Reduction with T-distributed stochastic neighbor embedding (t-SNE) on top of (PCA)  
-  3.4 Clustering
-  ...at least 80% of the paper ;-)
 
Part 4) Modelling the Claims Severity Data..........................................................................XXX  
Part 5) Results.............................................................................................XXX  
Part 6) Bibliography.......................................................................................................XXX  
Part 7) Annexe............................................................................................................XXX  

# List of Tested Algorithms  
  
Benchmark (Classic Linear Based Algorithms):

-  Linear Regression...............................................................................................XXX  
-  Linear Regression Ridge...............................................................................................XXX  
-  Linear Regression Lasso...............................................................................................XXX  
-  Linear Regression ElasticNet............................................................................................XXX  
 
Tree Based Algorithms:

-  Single Decision Tree Regressor.............................................................................................XXX  
-  Decision Tree Bagging Regressor............................................................................................XXX  
-  Random Forest Regressor...............................................................................................XXX  
-  Extra Trees Regressor...............................................................................................XXX  
-  Ada Boost Regressor...............................................................................................XXX  
-  Gradient Boosting Regressor...............................................................................................XXX  
-  XGBoost Regressor...............................................................................................XXX  
-  Light GBM Regressor...............................................................................................XXX
 
Neural Network and Stacking:

-  Neural Network with Keras (Tensorflow Backend).......................................................................XXX  
-  Neural Network with Tensorflow....................................................................................XXX  
-  Manual Stacking...............................................................................................XXX  
-  Marios Michailidis's StackNet.........................................................................................XXX 

Other Algorithms:

-  Support Vector Regression...............................................................................................XXX
-  K Neighbors Regressor...............................................................................................XXX

