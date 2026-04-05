
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
   3. Plotly  [==>]() -

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
    4. **Power transformer** [==>](5_Feature_Engineering/4_Power_Transformer/1_Power_Transformer.ipynb)
    5. **Numerical to Categorical features**  Binning [==>](5_Feature_Engineering/5_Numerical_To_Categorical/1_Binning.ipynb)
    6. **Handling mixed value** [==>](5_Feature_Engineering/6_Handling_Mixed_value/Mixed_value_handling.ipynb)
    7. **Missing data** 
       1. Univariate 
          1. Numerical 
             1. Mean-Median Imputation [==>](5_Feature_Engineering/7_Missing_Data/1_Univeriate/1_Numerical/1_Mean_Median_Imputation.ipynb)
             2. Arbitrary Imputation [==>](5_Feature_Engineering/7_Missing_Data/1_Univeriate/1_Numerical/2_Arbitary_Imputation.ipynb)
             3. Random Select Imputation [==>](5_Feature_Engineering/7_Missing_Data/1_Univeriate/1_Numerical/3_Numerical_Random_Select.ipynb)
          2. Categorical
             1. Frequent Value Imputation [==>](5_Feature_Engineering/7_Missing_Data/1_Univeriate/2_Categorical/1_Frequent_Value_Imputation.ipynb)
             2. Random Select Imputation [==>](5_Feature_Engineering/7_Missing_Data/1_Univeriate/2_Categorical/2_Random_select_Impute.ipynb)
       2. Multivariate 
          1. KNN multivariate impute (only numerical) [==>](5_Feature_Engineering/7_Missing_Data/2_Multivariate/1_KKN_Imputation.ipynb)
          2. Iterative impute [==>]() -
    8. **Outlier data** 
       1. Z-Score Filtering 
          - Using Mean Standardization [==>](5_Feature_Engineering/8_Outlier_Data/1_Z_Score_Filtering/1_Using_Mean_standarization.ipynb)
          - Using Z-Scoring [==>](5_Feature_Engineering/8_Outlier_Data/1_Z_Score_Filtering/2_Using_Zscore.ipynb)
       2. IQR Filtering [==>](5_Feature_Engineering/8_Outlier_Data/2_IQR_Filtering/1_IQR_Filtering.ipynb)
       3. Percentile Filtering [==>](5_Feature_Engineering/8_Outlier_Data/3_Percentile_Filtering/1_Percentile_Filtering.ipynb)
    9. **Feature construction and splitting** [==>]()
    10. **Handling date time** [==>]() - 
    11. **Complete case analysis** [==>]() - 
    12. **Features Importance**
         - Feature importance using random forrest [==>]() -

6. **Model**
   1. Supervised
        1. **Gradient Descent** 
           1. Gradient Descent for Single Column
              - BuildIn [==>](6_Model/1_Supervised_Learning/1_Gradient_Decend/1_For_Single_Feature/1_Single_col_gradient_descent.ipynb)
              - Own-class [==>](6_Model/1_Supervised_Learning/1_Gradient_Decend/1_For_Single_Feature/2_OwnClass_for_Gradient_Descent.ipynb)
           2. Batch Gradient Descent
              - BuildIn [==>](6_Model/1_Supervised_Learning/1_Gradient_Decend/2_Multiple_Features/1_Gradient_Descent.ipynb)
              - own-class [==>](6_Model/1_Supervised_Learning/1_Gradient_Decend/1_For_Single_Feature/2_OwnClass_for_Gradient_Descent.ipynb)
           3. Stochastic Gradient Descent 
              - BuildIn [==>](6_Model/1_Supervised_Learning/1_Gradient_Decend/3_Stochastic_Gradeint_Descent/1_BuildIn_Stochastic_Gradient_Descent.ipynb)
              - Own-class [==>](6_Model/1_Supervised_Learning/1_Gradient_Decend/3_Stochastic_Gradeint_Descent/2_Ownclass_Stochastic_Gradient_Descent.ipynb)
           4. Mini-Batch Gradient Descent
              - BuildIn [==>](6_Model/1_Supervised_Learning/1_Gradient_Decend/4_Mini_Batch_Gradeint_Descent/1_BuildIn_Mini_Batch_Gradient_Descent.ipynb)
              - Own-class [==>](6_Model/1_Supervised_Learning/1_Gradient_Decend/4_Mini_Batch_Gradeint_Descent/2_Ownclass_Mini_Batch_Gradient_Descent.ipynb)
        2. **Linear Regression**  
           1. One Dimensional Linear Regression 
               - BuildIn [==>](6_Model/1_Supervised_Learning/2_Linear_Regression/1_One_Dimentional_Linear_Regression/1_BuildIn_One_Dimentional_Linear_Regression.ipynb)
               - Own-class [==>](6_Model/1_Supervised_Learning/2_Linear_Regression/1_One_Dimentional_Linear_Regression/2_Ownclass_One_Dimentional_Linear_Regression.ipynb)
           2. Multi Dimensional Linear Regression 
               - BuildIn [==>](6_Model/1_Supervised_Learning/2_Linear_Regression/2_Linear_Regression_Multi_Dimentional/1_BuildIn_Linear_Regression_Multi_Dimentional.ipynb)
               - Own-class [==>](6_Model/1_Supervised_Learning/2_Linear_Regression/2_Linear_Regression_Multi_Dimentional/2_Ownclass_Linear_Regression_Multi_Dimentional.ipynb)
           3. Polynomial Regression 
              - BuildIn [==>](6_Model/1_Supervised_Learning/2_Linear_Regression/3_Polynomial_Regression/1_BuildIn_Polynomial_Regression.ipynb)
              - Custom-class [==>](6_Model/1_Supervised_Learning/2_Linear_Regression/3_Polynomial_Regression/2_Customization_Polynomial_Regression.ipynb)
           4. Ridge Regression 
              - BuildIn [==>](6_Model/1_Supervised_Learning/2_Linear_Regression/4_Ridge_Regression/1_BuildIn_Ridge_Regression.ipynb)
              - Own-class (One Dimension) [==>](6_Model/1_Supervised_Learning/2_Linear_Regression/4_Ridge_Regression/2_Ownclass_oneDim_Ridge_regression.ipynb)
              - Own-class (Multidimensional) [==>](6_Model/1_Supervised_Learning/2_Linear_Regression/4_Ridge_Regression/3_Ownclass_multiDim_Ridge_regression.ipynb)
           5. Lasso Regression [==>](6_Model/1_Supervised_Learning/2_Linear_Regression/5_Lasso_Regression/1_Lasso_Regression.ipynb)
        3. **Logistic Regression**
           1. Perception Trick [==>](6_Model/1_Supervised_Learning/3_Logistic_Regression/1_Perception_Trick/Perception_Trick.ipynb)
           2. Logistic regression using Gradient Descent
               1. Binary Class Classification 
                  1. BuildIn [==>](6_Model/1_Supervised_Learning/3_Logistic_Regression/2_Using_Gradient_Descent/1_Binary_Class_Classification/1_BuildIn_Binary_Class_Classification.ipynb)
                  2. Own-class [==>](6_Model/1_Supervised_Learning/3_Logistic_Regression/2_Using_Gradient_Descent/1_Binary_Class_Classification/2_Ownclass_Binary_Class_Classification.ipynb)
               2. Multiclass Classification (softmax) [==>](6_Model/1_Supervised_Learning/3_Logistic_Regression/2_Using_Gradient_Descent/2_Multi_Class_Classification/Multi_Class_Classification.ipynb)
               3. Polynomial or Non-linear Logistic Regression  [==>](6_Model/1_Supervised_Learning/3_Logistic_Regression/2_Using_Gradient_Descent/3_Polynomial_Classifier/1_Polynomial_Classification.ipynb)
           3. Accuracy Metrics 
              - Binary class [==>](6_Model/1_Supervised_Learning/3_Logistic_Regression/3_Accuracy_Metrices/1_Binary_Class_Classification.ipynb)
              - Multi class [==>](6_Model/1_Supervised_Learning/3_Logistic_Regression/3_Accuracy_Metrices/2_Multi_Class_Classification.ipynb) 
        4. **Decision Tree** 
           1. Classification Decision Tree
              1. Decision Tree Classifier [==>](6_Model/1_Supervised_Learning/4_Decision_Tree/1_Decision_Tree_Classifier/1_Decision_Tree_Classifier.ipynb)
              2. Decision Tree Classifier Hyperparameter Tuning [==>](6_Model/1_Supervised_Learning/4_Decision_Tree/1_Decision_Tree_Classifier/2_Decision_Tree_Classifier_Hyperparameter_Tuning.ipynb)
           2. Regression Decision Tree
              1. Decision Tree Regressor [==>](6_Model/1_Supervised_Learning/4_Decision_Tree/2_Decision_Tree_Regression/1_Decision_Tree_Regressor.ipynb)
              2. Decision Tree Regressor Hyperparameter Tuning [==>](6_Model/1_Supervised_Learning/4_Decision_Tree/2_Decision_Tree_Regression/2_Decision_Tree_Regression_Hyperparameter_Tuning.ipynb)
        5. **Naive Bayes** [==>]()
        6. **K-Nearest Neighbours (KNN)** 
           - Classification [==>](6_Model/1_Supervised_Learning/6_K_Nearest_Neighbours/1_KNN_Classification.ipynb)
        7. **Supportive Vector Machine (SVM)**
           - Classification [==>](6_Model/1_Supervised_Learning/7_Supportive_Vector_Machine/1_SVM_Classification.ipynb)
        8. **Ensemble Learning**
              1.  **Voting** 
                  1. Voting classifier 
                     1. Binary Classification[==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/1_Voting/1_Classification_Voting/1_Voting_Binary_Classifier.ipynb)
                     1. Multi Class Classification[==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/1_Voting/1_Classification_Voting/2_Voting_Multi_Classifier.ipynb)
                  2. Voting regressor  [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/1_Voting/2_Regression_Voting/1_Voting_Binary_Regressor.ipynb)
              2. **Bagging**
                 1. Different Algorithm Bagging
                    1. Bagging Classification [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/2_Bagging/1_Bagging_Algorithms/1_Bagging_Classification/1_Bagging_Classifier.ipynb)
                    2. Bagging Regression [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/2_Bagging/1_Bagging_Algorithms/2_Bagging_Regression/1_Bagging_Regressor.ipynb)
                 2. Bootstrapping in Bagging
                       1. With replacement Bootstrapping (Row sampling With replacement ) [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/2_Bagging/2_Different_Bootstraping_In_Bagging/1_With_replacement.ipynb) 
                       2. Pasting Bootstrapping (Row sampling Without replacemnet)  [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/2_Bagging/2_Different_Bootstraping_In_Bagging/2_Pasting.ipynb)
                       3. Random subspace Bootstrapping (col sampling + no row sampling) [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/2_Bagging/2_Different_Bootstraping_In_Bagging/3_Random_Subspace.ipynb)
                       4. Random patch Bootstrapping  (col sampling + row sampling can (replacement / not)) [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/2_Bagging/2_Different_Bootstraping_In_Bagging/4_Random_Patch.ipynb)
                 3. Random Forrest
                    1. Random forrest Algorithm  
                       1. Classification using Random Forest [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/2_Bagging/3_Random_Forrest/1_Random_Forrest_Algorithm/1_Random_Forrest_Classification.ipynb)
                       2. Regressor using Random Forest [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/2_Bagging/3_Random_Forrest/1_Random_Forrest_Algorithm/2_Random_Forrest_Regression.ipynb)
                    2. Bootstrapping in Random forrest  [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/2_Bagging/3_Random_Forrest/2_Different_Bootstraping_In_Random_Forest/1_Different_Bootstraping_In_Random_Forest.ipynb)
              3. **Boosting**
                 1. Adaboost 
                    1. Adaboost Classification 
                       1. Adaboost Classifier  [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/3_Boosting/1_Adaboost/1_Adaboot_Classification/1_Adaboost_Classifier.ipynb)
                       2. Adaboost Step by Step  [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/3_Boosting/1_Adaboost/1_Adaboot_Classification/2_Algorithm_Clarrification.ipynb)
                    2. Adaboost Regression [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/3_Boosting/1_Adaboost/2_Adaboot_Regressor/1_Adaboost_Regressor.ipynb)
                 2. Gradient Boosting 
                    1. Gradient Regression 
                       1. Gradient Boosting Regression  [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/3_Boosting/2_Gradient_Boosting/1_Regression_Gradeint_Boosting/1_Regression_Gradeint_Boosting.ipynb)
                       2. Gradient Step by Step Additive Modeling  [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/3_Boosting/2_Gradient_Boosting/1_Regression_Gradeint_Boosting/2_Additive_Modeling_Regression.ipynb)
                    2. Gradient Boosting Classification [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/3_Boosting/2_Gradient_Boosting/2_Classification_Gradient_Booting/1_Classification_Gradient_Booting.ipynb)
            
                 3. XG Boosting 
                    1. XG Boosting Regression [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/3_Boosting/3_XG_Boosting/1_Regression_XG_Boosting/1_Regression_XG_Boosting.ipynb)
                    2. XG Boosting Classification [==>](6_Model/1_Supervised_Learning/8_Ensemble_Learning/3_Boosting/3_XG_Boosting/2_Classification_Gradient_Booting/1_Classification_XG_Booting.ipynb)
              4. **Stacking**
                 1. Blending Stacking [==>]()
   2. Unsupervised
      1. **K Means Clustering** [==>](6_Model/2_Unsupervised_Learning/1_K_Nearest_Neighbour_KNN/1_KNN_Classifier.ipynb) 
      2. **Hierarchical Clustering**  [==>]()
      3. Dimensionality Reduction (PCA) [==>]() 