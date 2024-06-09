# FeatureX: An Explainable Feature Selection for Deep Learning
Feature selection, as a data preprocessing method, is of great significance in reducing dimension disaster and improving model performance. However, the majority of feature selection methods lack explainability when selecting features. When one feature is prioritized over another, few techniques provide quantitative information about this selection. Furthermore, existing feature selection techniques require users to provide corresponding thresholds or parameters to drive algorithm execution. However, in most cases, it is difficult for users to determine the optimal threshold or parameter for the current task. To address these problems, this paper proposes an explainable feature selection method called FeatureX. <br>
FeatureX combines feature perturbation, feature importance analysis, and statistical analysis to filter features. It also designs a feature importance analysis method based on feature perturbation to quantify the contribution value of features to the model. With the feature contribution and correlation coefficients, FeatureX screens these features to automatically identify the most relevant and high-contribution features. <br>
The experimental results show that the number of features is reduced by an average of 47.83%, and 63.33% of the models illustrate an improved accuracy compared to the previous one.
## Dataset 
The source part of the dataset is available at the following URL [Dataset.rar](https://github.com/aaaa-res/FeatureX/blob/main/Dataset.rar) <br>
## Feature Importance Analysis
The code for feature importance analysis is available at the following URL [Data_perturbation.ipynb](https://github.com/aaaa-res/FeatureX/blob/main/Data_perturbation.ipynb) <br>
##  Correlation Analysis
The code for correlation analysis is available at the following URL [correlation_analysis.ipynb](https://github.com/aaaa-res/FeatureX/blob/main/correlation_analysis.ipynb) <br>
##  Feature Selection
The code for feature selection is available at the following URL [Feature_selection.ipynb](https://github.com/aaaa-res/FeatureX/blob/main/Feature_selection.ipynb) <br>
