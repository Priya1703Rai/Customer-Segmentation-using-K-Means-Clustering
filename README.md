# Customer-Segmentation-using-K-Means-Clustering
1.Data Analysis:

Null Values: It identifies and removes rows with missing values to prepare for clean analysis and modeling.
Visual Analysis: Distribution plots (distplots) for features like age, work experience, and family size reveal data patterns and provide insight into how these features vary across the dataset.

2.Segmentation Analysis: It analyzes mean values for features by customer segments, possibly indicating differences in customer behavior or demographics.
Grouping by Gender and Profession: Analyzing these factors reveals insights into spending habits or preferences based on gender and profession, which may help refine customer segmentation.

3.Data Visualization:
Bar plots and pair plots are created to visualize relationships among variables and how they align with different customer segments.
A correlation heatmap illustrates feature relationships, showing which variables are closely associated.

4.Data Preprocessing:
One-Hot Encoding is used to convert categorical variables into a numerical format suitable for machine learning models.
This step transforms the data for compatibility with models and ensures that categorical values don’t impose an order on the data.

5.Model Building:
The code seems to test several classification models, including LogisticRegression, DecisionTreeClassifier, RandomForestClassifier, GaussianNB, KNeighborsClassifier, and SVC.
Supervised Approach: Although segmentation typically involves unsupervised learning (like K-Means clustering), this project seems to treat the segmentation as a classification problem, likely using pre-labeled data for customer segments.

6.Evaluation:
Accuracy scores, classification reports, and confusion matrices evaluate model performance, providing insights into which algorithm best classifies the segments.

Summary
The project primarily uses data visualization and supervised learning models to segment customers based on attributes such as age, gender, profession, and spending habits. The approach combines both clustering analysis (typical in segmentation projects) and classification to potentially predict customer segments based on historical data.
