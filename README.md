<h1>K-Nearest Neighbors Classification for Hospital Patient Readmission Risk</h1>
<br>
<h2> Project Description/Purpose</h2>
<br>
The goal of the Hospital Readmission Reduction Program is to reduce excess hospital readmissions. To accomplish this, hospital systems that are found to have excessive readmission rates are financially penalized. As such, it is in the best interest of hospital executives to identify factors contributing to patient readmission. This analysis provides a k-nearest neighbors classification model to predict a hospital patient’s readmission risk based on patient medical conditions and initial hospitalization factors.
<br>
<br>
<h2> Tools Used For Analysis</h2>
<br>
<b>Data:</b> The data used for this analysis were obtained from Western Governors University. The data are part of the Master of Science: Data Analytics degree resources and are not available publicly. The data set represents a fictitious hospital system and gives information on patient demographics, medical conditions, initial hospitalization experience, readmission state, and patient satisfaction survey results. This analysis used the readmission status as the target variable, and patient medical conditions and initial hospitalization information as features.
<br>
<br>
All parts of this analysis were conducted using Python in a Jupyter notebook. The Python libraries and modules used for this analysis included:
<br>
<ul>
  <li>Pandas</li>
  <li>Numpy</li>
  <li>Matplotlib.pyplot</li>
  <li>Seaborn</li>
  <li>train_test_split from sklearn.model_selection</li>
  <li>KNeighborsClassifier from sklearn.neighbors</li>
  <li>StandardScaler from sklearn.preprocessing</li>
  <li>GridSearchCV from sklearn.model_selection</li>
  <li>classification_report from sklearn.metrics</li>
  <li>confusion_matrix and plot_confusion_matrix from sklearn.metrics</li>
  <li>mosaic from statsmodels.graphics.mosaicplot</li>
  <li>roc_curve and roc_auc_score from sklearn.metrics</li>
</ul>
<br>
<h2> Summary of Findings</h2>
<br>
A summary of the key findings can be found in the executive summary linked <a href="https://docs.google.com/presentation/d/152aJS15ZDkLSTVCWj-hCv2qhNnMqcEnqGL5vF4EMGYQ/edit?usp=sharing">here.</a>
<br>
<h2> Resources</h2>
<br>
<ul>
  <li><b>Python Code:</b> The Python code used in this project can be examined in the <a href="https://github.com/cfuller19/knearestneighbors/blob/main/knn_classifier.ipynb">code section of this repository.</a></li>
</ul>
