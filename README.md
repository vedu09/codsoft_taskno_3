# codsoft_taskno_3

# codsoft_taskno_4
<h1>Author : VEDANT GHADGE</h1>

<h1>Title : IRIS FLOWER CLASSIFICATION USING PYTHON</h1>



<h2>Introduction :</h2>
<p>In this project, our goal is to create a model capable of sorting iris flowers into distinct species by examining their sepal and petal measurements. By analyzing these characteristics, we aim to develop a reliable classification system that can distinguish between various iris species, contributing to a better understanding of these beautiful flowers and their unique attributes.</p>

<h2>Dataset</h2>
<p>For this project, the primary dataset is sourced from the "IRIS.csv" file, encompassing five crucial columns: 'sepal_width', 'sepal_length', 'petal_width', 'petal_length', and 'species'. The dataset provides comprehensive measurements of iris flowers, capturing details such as sepal and petal dimensions. To initiate our analysis, the dataset was seamlessly loaded into our Python environment utilizing the `pandas` library's `read_csv()` function. This dataset serves as the foundation for our exploration, allowing us to delve into the intricate characteristics of iris flowers and pave the way for the development of a robust classification model.</p>

<h2>Library Used</h2>
<p>Following Libraries were used in the project :</p>
<ul><li>pandas</li>
    <li>numpy</li>
    <li>matplotlib</li>
    <li>seaborn</li>
    <li>sklearn.svm.SVC</li>
    <li>sklearn.model_selection.train_test_split, .cross_val_score</li>
    <li>sklearn.preprocessing.StandardScaler</li>
    <li>sklearn.metrics.classification_report, .accuracy_score, .confusion_matrix</li>
</ul>

<h2>Data Exploration and Preprocessing</h2>
<ul>
    <li>The structure and summary statistics of the dataset were unveiled through the implementation of `df.shape` to ascertain its dimensions and `df.describe()` to present a comprehensive overview of its key statistical measures.</li>
    <li>Missing values in the dataset were checked using df.isna().sum().</li>
    <li>If any missing values are found they were droped by df.dropna() function</li>
</ul>


<h2>Data Visualization</h2>
<ul>
    <li>2D scatter plots were created w.r.t species to visualize the relationship between seopal_width and sepal length, as well as between petal_width and petal_length using seaborn.scatterplot.</li>
    <li>Pair plot was created to visualize relationships among all features</li>
</ul>



<h2>Model Training</h2>
<ul>
    <li>The dataset was divided into training and testing sets using `train_test_split`.</li>
    <li>Support Vector Machine (SVM) model was trained on the training data using `sklearn.svm.SVC`.</li>
</ul>

<h2>Model Results</h2>
<ul>
    <li>The model was predicted for the test set using 'svm_classifier.predict(x_test)'.</li>
    <li>Accuracy Score was calculated which was 97.37% using 'accuracy_score(y_test,y_predict)'</li>
    <li>Classification Report was created using 'classification_report(y_test,y_predict)'</li>
</ul>

<h2>Testing Model</h2>
<ul>
    <li>The confusion matrix was calculated to evaluate the accuracy of the SVM Algorithm.</li>
    <li>Accuracy of Confusion Matrix was calculated by using 'cross_val_score(x_train,y_train)'.</li>
</ul>
