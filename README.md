# Dibatese_detection-using-ML
This project on diabetes prediction was particularly compelling to me for several reasons.
Firstly, diabetes is a widespread and growing health concern globally, affecting millions of individuals. 
By working on this project, I wanted to contribute to the field of healthcare by developing a predictive model that can assist in early detection and intervention.

# Through this project, we have learned several important concepts and skills related to machine learning and data analysis. Here are some key takeaways:
1. Data Preprocessing: We gained hands-on experience in preprocessing the dataset, which involved handling missing values, performing feature scaling, and exploring data distribution.
2. Exploratory Data Analysis (EDA): We performed EDA to gain insights into the dataset, visualized data using various plots and charts, and examined the relationships between different features.
3. Feature Selection and Engineering: We analyzed the correlation between features and the target variable to identify important features for prediction. We also created new features based on domain knowledge and feature interactions.
4. Model Selection and Evaluation: We explored different machine learning algorithms such as Logistic Regression, Decision Trees, Random Forests, and Support Vector Machines (SVM). We used evaluation metrics like accuracy, precision, recall, and F1-score to assess the performance of the models.
5. Hyperparameter Tuning: We utilized techniques like GridSearchCV to find the best hyperparameters for the models, enhancing their performance and generalization.
6. Model Deployment: We built a web application using Streamlit, where users can input their medical information and obtain predictions of their diabetes risk in real-time.
7. Collaboration and Version Control: We worked collaboratively on the project, utilizing Git and GitHub for version control and seamless collaboration

![image](https://github.com/muskanjhjh24/Dibatese_detection-using-ML/assets/80843279/2e96a225-8895-4a6d-969e-a220c0424293)

# Approach
# A. DATA PREPROCESSING:
When applying machine learning techniques to a dataset, one of the most crucial processes for accurate results and effective prediction is data preprocessing. The majority of data in the healthcare industry has missing values and other contaminants, which might reduce the usefulness of the data.
Data preprocessing for the Pima Indians dataset was carried out in five steps.
1) Importing Python Libraries: To work with the data, Python libraries were imported. Pandas, numpy, matplotlib.pyplot, seaborn, and warnings were a few of the
Python libraries imported.
2) Elimination of blank values: A feature subset is generated by removing pointless features and instances; this procedure is known as features subset selection. It
speeds up work by reducing the number of dimensions in the data.
3) Looking for zero values: The X data set had 768 zero values (Independent variables). The model might not have been as effective as a result. In order to impute the zero values, utilize the mean function.
4) Standardization: Z-Score or standardization By deducting from the mean and dividing by the standard deviation, characteristics are transformed through
normalization. The Z-score is a common name for this. The algorithm may favor attributes with high magnitude without standardization.
5) Visualizing associations in the dataset: A heatmap was created to help us understand the information we are working with. Additionally, it aids in comprehending the
Brighter colors in the heatmap above suggest a higher correlation. Glucose levels, age, BMI, and the number of pregnancies all have strong correlations with the outcome
variable, as shown in the table and heatmap.
6) Splitting the Data: When the data is split, algorithms are trained on the training data set and the test data is kept aside. The aim of normalization is to bring all the attributes under the same scale. The training and test data is split in the ratio of 80:20.

# B. APPLYING MACHINE LEARNING TECHNIQUES:
On the dataset, the following machine learning algorithms were applied.

1) Support Vector Machine (SVM): Support Vector Machines are a collection of learning algorithms and supervised learning models that analyze and investigate
data for classification, regression, and outlier detection. It seeks to identify an N-dimensional hyperplane in which to
clearly classify the dataset. SVM has a few advantages, including the fact that it performs well in situations with several dimensions. The decision function uses a subset of training points known as support vectors to conserve
memory.

2) Logistic Regression: Based on simulating the probability of a discrete result given the fed data, logistic regression is a classification technique. The
implementation is simple to carry out and exhibits effective performance for linear and binary classification. It helps classify a new sample into the preexisting sets. It makes no presumptions regarding the distributions of classes in feature space. Multinomial regression offers a natural probabilistic approach of class prediction and is easy to extend to several classes. It swiftly classifies
records that are unfamiliar.

3) Decision Tree: A decision tree is a powerful and well-liked tool used for classification and prediction. It is a nonparametric supervised learning algorithm with a flowchart-like structure. It can be described as a decision-support tool with a tree-like structure, where the nodes stand in for the qualities tested, the branches for the results of the tests, the leaves for the class labels, and the path from the root to the leaf for the classification rule. Decision tree
classification doesn't require a lot of computational power. Decision trees are capable of handling both continuous and categorical inputs. The most important fields for
classification or prediction are displayed by decision trees.

4) Random Forest: Random Forest is a supervised machine learning technique that is popularly used for classification and regression. It tries to enhance predictive
performance by resulting in the prediction of many models. On various samples, it creates several decision trees, and for the classification process, the result is the
class selected by the majority of the trees as well as the mean prediction of the trees. Both continuous and categorical data can be handled by it. The procedure of
adding missing values to data is automated. It uses a rule-based methodology, therefore no data standardization is required.


# C. BUILDING THE WEB APPLICATION:
An open-source Python framework called Streamlit is used to create web apps for machine learning. The development process is quick and easy when utilizing
Streamlit as opposed to other machine learning software frameworks. Changes can be made directly in the source code after a Streamlit server has operated, and the
application will update to reflect the changes. Pandas, Sklearn, matplotlib, and PIL (Python Imaging Library) were some of the libraries used in this procedure.
In order to reduce typing, a slider-based input technique was employed in the online application.


# Steps to run the project
1. Take the Diabetes_prediction.py file and open it with vs code, also upload the dataset diabetes.csv on the same working directory
2. Run each cell one by one, we will get the model.pk file which is our trained model.
3. Now for a better UI and user-friendly interface take the app.py file and open it with vs code under the same folder.
4. Run that file and Check the response.
5. Enjoy :)

