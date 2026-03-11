
# Machine Learning

1. **Data Structure**
   1. Numpy 
      - Basic [==>](1_Data_Structure/1_Numpy/1_Numpy_Basis.ipynb)
      - Advance [==>](1_Data_Structure/1_Numpy/2_Numpy_Adv.ipynb)
   2. Pandas 
      1. Series [==>](1_Data_Structure/2_Pandas/1_Series_Pandas.ipynb)
      2. Dataframe [==>](1_Data_Structure/2_Pandas/2_Dataframe_Pandas.ipynb)

2. **Data Visualization**
   1. Matplotlib [==>](2_Data_Visualization/1_Matplotlib/Matplotlib.ipynb)
      1. Uni variate analysis
         1. Histogram 
      2. Uni variate and Bivariate Analysis
         1. Pie Chart
      3. Bivariate and Multivariate analysis
         1. 2D Line Plot
         2. 3D Line Plot
         3. Scatter Plot
         4. 3D Scatter Plot
         5. 3D Surface Plot
         6. Contour Plots
         7. Heatmap
         8. Bar Chart
      4. Sub Plot
      
   2. seaborn [==>](2_Data_Visualization/2_Seaborn/Seaborn.ipynb)
      1. Relation Plot
         1. Scatter Plot
         2. Facet Plot
         3. Line Plot
         
      2. Distribution Plot
         1. Histogram
         2. Facet Histogram
         3. Bivariate Histogram
         4. Kde plot
         5. Bivariate Kde plot 
         6. Rug plot 
         
      3. Categorical Plot
         1. Categorical Scatter Plot (Bi variate analysis)
            1. Stripplot
            2. Swarmplot
         2. Categorical Distribution Plots (Single variate analysis)
            1. Boxplot
            2. Violinplot 
         3. Categorical Estimate Plot (for central tendency)
            1. Barplot
            2. Pointplot
            3. Countplot
      4. Matrix Plot
         1. Heatmap
         2. Clustermap
      5. Regreession Plot
      6. Multiplots
         1. facetplot
         2. jointplot
         3. pairplot
   3. Plotly  [==>]()

3. **Data Gathering** 

   1. CSV data [==>](3_Data_Gathering/1_CSV_data.ipynb)
   2. JSON data [==>]()
   3. API data  [==>]() 
   4. Web scraping [==>]() 

4. **Data Analysis** 

   1. **Understanding data** [==>](4_Data_Analysis/1_Understanding_Data/1_Understanding_Data.ipynb)
   2. **EDA** 
      1. Univariate [==>](4_Data_Analysis/2_EDA/1_Univariate_analysis.ipynb) 
      2. Multivariate [==>](4_Data_Analysis/2_EDA/2_Multi_Variate_analysis.ipynb)

5. **Features Engineering**
    1. **Feature transformation**
          1. Standardization  [==>](5_Feature_Engineering/1_Feature_Transformation/1_Standardization.ipynb)
          2. Normalization [==>](5_Feature_Engineering/1_Feature_Transformation/2_Normalization.ipynb)
    2. **Handling categorical features** 
       1. Ordinal encoding [==>](5_Feature_Engineering/2_Handling_Categorical_Features/1_Ordinal_Encoding.ipynb)
       2. One Hot encoding [==>](5_Feature_Engineering/2_Handling_Categorical_Features/2_One_Hot_Encoding.ipynb)
    3. **Pipelines** 
       Column transformer [==>](5_Feature_Engineering/3_Pipelines/1_Column_transformer.ipynb)

    4. **Transformer**
       1. Functional transformer 
          - Without Functional transformer  [==>]()
          - Using Functional transformer  [==>]()
       2. Power transformer [==>]()
    5. **Numerical to Categorical features**  Binning [==>]()
    6. **Handling mixed value** [==>]()
    7. **Missing data** 
       1. Univariate 
          1. Numerical 
             1. Mean-Median Imputation [==>]()
             2. Arbitrary Imputation [==>]()
             3. 1. Random Select Imputation [==>]()
          2. Categorical
             1. Frequent Value Imputation [==>]()
             2. Missing column [==>]()
             3. Random Select Imputation [==>]()
       2. Multivariate 
          1. KNN multivariate impute [==>]()
          2. Iterative impute [==>]()
    8. **Outlier data** 
       1. Z-Score Filtering 
          - Using Mean Standardization [==>]()
          - Using Z-Scoring [==>]()
       2. IQR Filtering [==>]()
       3. Percentile Filtering [==>]()
    9. **Feature construction and splitting** [==>]()
    10. **Handling date time** [==>]()
    11. **Complete case analysis** [==>]()
    
    12. **Features Importance**
         - Feature importance using random forrest [==>]()

6. **Model**
   1. Supervised
        1. **Gradient Descent** 
           1. Gradient Descent for Single Column
              - BuildIn [==>]()
              - own-class [==>]()
           2. Batch Gradient Descent
              - BuildIn [==>]()
              - Own-class [==>]()
           3. Stochastic Gradient Descent 
              - BuildIn [==>]()
              - Own-class [==>]()
           4. Mini-Batch Gradient Descent
              - BuildIn [==>]()
              - Own-class [==>]()
        2. **Linear Regression**  
           1. One Dimensional Linear Regression 
               - BuildIn [==>]()
               - Own-class [==>]()
           2. Multi Dimensional Linear Regression 
               - BuildIn [==>]()
               - Own-class [==>]()
           3. Polynomial Regression 
              - BuildIn [==>]()
              - Own-class [==>]()
           4. Ridge Regression 
              - BuildIn [==>]()
              - Own-class (One Dimension) [==>]()
              - Own-class (Multidimensional) [==>]()
           5. Lasso Regression [==>]()
        3. **Logistic Regression**
           1. Perception Trick 
              - Using Step Function [==>]()
              - Using Sigmoid Function [==>]()  
           2. Logistic regression using Gradient Descent
               1. Binary Class Classification [==>]()
               2. Accuracy score (Metrics) 
                  - Binary class [==>]()
                  - Multi class [==>]()
               3. Multinomial(multiclass) Classification (softmax) [==>]()
               4. Polynomial or Non-linear Logistic Regression  [==>]()
        4. **Decision Tree** 
           1. Classification [==>]()
           2. Regression [==>]()
        5. **Naive Bayes** [==>]()
        6. **K-Nearest Neighbours (KNN)** 
           - Classification [==>]()
        7. **Supportive Vector Machine (SVM)**
           - Classification [==>]()
      8. Ensemble Learning
         1.  **Voting** 
             1. Voting classifier [==>]()
             2. Voting regressor  [==>]()
         2. **Bagging**
            1. Different Algorithm Bagging 
               1. Bootstrapping in Bagging
                  1. With replacement Bootstrapping [==>]() 
                  2. Pasting Bootstrapping  [==>]()
                  3. Random subspace Bootstrapping [==>]()
                  4. Random patch Bootstrapping  -
               2. Bagging Classification [==>]()
               3. Bagging Regression [==>]()
            2. Random Forrest 
               1. Bootstrapping in Random forrest  [==>]()
               2. Random forrest Algorithm  
                  - Plotting random forrest [==>]()
                  - Search CV in random forrest [==>]()
         3. **Boosting**
            1. Adaboost 
               1. Adaboost Implementation [==>]()
               2. Adaboost hyperparameter tuning [==>]()
            2. Gradient Boosting 
               1. Gradient Boosting [==>]()
               2. Additive modelling Regression [==>]()
               3. Additive modelling Classification [==>]()
            
            3. XG Boosting [==>]()
         4. **Stacking**
            1. Blending Stacking [==>]()
   2. Unsupervised
      1. **K Means Clustering** [==>]() 
      2. **Hierarchical Clustering**  [==>]()
      3. Dimensionality Reduction (PCA) [==>]() 