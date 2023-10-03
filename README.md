# breast-cancer-prediction
Introduction

Breast cancer is a disease that causes a high mortality rate in women. This disease is caused by breast tissue cells that grow abnormally and continuously. Family history of breast cancer, menopausal age, age of first child pregnancy, nulliparous parity, breastfeeding history, obesity, and activity are some of the high risk factors that can cause breast tumor cancer (Hero 2021).

Data Understanding

In our project, we've harnessed the power of data by loading a comprehensive breast cancer dataset from a CSV file. This dataset encompasses a myriad of features characterizing breast tumor cells, providing a rich source of information for analysis. Our primary focus revolves around the target variable, the diagnosis, where 'M' signifies malignancy, indicating the presence of cancer cells with harmful effects, while 'B' denotes benign cases, signifying the absence of cancer and non-harmful cells. This crucial understanding of the data's context is instrumental in our pursuit to uncover meaningful insights and develop predictive models for breast cancer diagnosis, ultimately contributing to better healthcare decision-making and patient outcomes.

Exploratpory Data Analysis

Our data exploratory analysis (EDA) reveals a notable class imbalance, with more entries for benign cases than malignant ones. Additionally, attributes like texture, smoothness, and symmetry exhibit Gaussian or nearly Gaussian distributions.
Heatmap analysis shows strong positive correlations between mean area and mean radius/perimeter, while concavity and area/perimeter have moderate correlations. Fractal dimension shows a strong negative correlation with mean radius, perimeter, and area.
In summary, mean values of specific attributes seem crucial for cancer classification, with larger values indicating a potential link to malignancy. Importantly, our data lacks noticeable outliers, reducing the need for extensive data cleaning. These insights inform our subsequent breast cancer diagnosis modeling efforts.

Model Building

We split the dataset into training and testing sets, scaled features using StandardScaler, and utilized logistic regression for model training and prediction. This approach ensures a robust and reliable breast cancer diagnosis model.

Model Evaluation

We conducted a thorough model evaluation, yielding impressive results with a ROC AUC score of 97.1% and an F1 score of 97.9%. Additionally, we scrutinized the confusion matrix, providing detailed insights into the model's classification accuracy. These outcomes underscore the robustness and reliability of our breast cancer diagnosis model, instilling confidence in its real-world applicability.
