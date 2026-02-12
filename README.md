# Supervise-learning-project

<h1>Credit Wise - Loan Approval Prediction</h1>
<br>
Credit Wise is a machine learning project designed to automate the process of loan approval prediction. By analyzing applicant data such as income, credit score, and financial history, the model provides an accurate prediction of whether a loan should be approved or rejected.
<br>
<h2>Project Overview</h2>
<br>
The goal of this project is to build a classification model that minimizes financial risk for lenders while ensuring fair loan opportunities for applicants. The project involves comprehensive data preprocessing, exploratory data analysis (EDA), and the implementation of several supervised learning algorithms.
<br>
<h2>Key Features</h2>
<ul>
    <li>
        <strong>Data Imputation:</strong> Automatic handling of missing numerical and categorical values.
    </li>
    <li>
        <strong> Exploratory Data Analysis (EDA):</strong> Visual insights into class balance and feature distributions.
    </li>
    <li>
        <strong> Feature Engineering:</strong> Scaling and encoding of data for optimal model performance.
    </li>
    <li>
        <strong> Multi-Model Comparison:</strong> Implementation of Logistic Regression, Random Forest, Support Vector Machines (SVM), and Naive Bayes.
    </li>
    </ul>

<h2>Dataset</h2>
<br>
The project utilizes a loan approval dataset with 20 features, including:
<ul>
    <li>
        <strong>Applicant Demographics:</strong> Age, Gender, Education, Marital Status.
    </li>
    <li>
        <strong> Financial Details: </strong> Applicant Income, Savings, Credit Score, Debt-to-Income (DTI) Ratio.
    </li>
    <li>
        <strong> Loan Specifics:</strong> Loan Amount, Loan Purpose, Collateral Value.
    </li>
    <li>
        <strong> Target Variable:</strong> Loan_Approved (Yes/No).
    </li>
</ul>
    <br>
<h2>Technical Implementation</h2><br>
<h3> Preprocessing </h3> <br>
<ul>
    <li> 
        <strong>Handling Missing Values:</strong> Numerical columns are imputed using the mean strategy, and categorical columns using the most_frequent strategy.
    </li>
</ul>
<ul>
    <li> 
        <strong>Data Scaling:</strong> Standard scaling is applied to ensure numerical features are on a comparable scale.
    </li>
</ul>

<h2>Models Used</h2> <br>
The following models were trained and evaluated:

<ol>
<li>
    <strong>Logistic Regression:</strong> For baseline classification.
</li>
<li> 
    <strong>Random Forest:</strong> To handle non-linear relationships.
</li>
<li>
    <strong> SVM (Support Vector Machine):</strong>Using RBF kernels.
</li>
<li>
    <strong>Naive Bayes:</strong> For probabilistic classification.
</li>
</ol>
