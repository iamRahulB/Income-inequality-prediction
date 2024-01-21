<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>

  <h1>Income Inequality Prediction</h1>

  <h2>Description</h2>

  <p>Income inequality, characterized by an uneven distribution of income within a population, poses a significant challenge in developing nations worldwide. The rise of artificial intelligence and worker automation further exacerbates this issue. Addressing income inequality is crucial, and this project aims to contribute by providing a solution to monitor key population indicators, specifically income levels between census years. The goal is to reduce costs and enhance the accuracy of tracking income distribution, aiding policymakers in effectively managing and mitigating global income inequality.</p>

  <h2>Problem Statement</h2>

  <p>The target feature is <code>income_above_limit</code>, a binary-class variable. The objective is to develop a machine learning model capable of predicting whether an individual earns above or below a certain income threshold. The primary evaluation metric for the model's performance is the <code>f1-score</code>.</p>

  <h2>Model Evaluation</h2>

  <h3>Random Forest Classifier</h3>

  <pre>
                  precision    recall     f1-score    support
            0       1.00        0.98      0.99         39578
            1       0.98        1.00      0.99         39023

    accuracy                              0.99         78601
    macro avg       0.99        0.99      0.99         78601
    weighted avg    0.99        0.99      0.99         78601
  </pre>

  <h3>XGBoost Classifier</h3>

  <pre>
                  precision    recall    f1-score   support
            0       0.93        0.89      0.91       39578
            1       0.89        0.93      0.91       39023

    accuracy                              0.91       78601
    macro avg       0.91        0.91      0.91       78601
    weighted avg    0.91        0.91      0.91       78601
  </pre>


  <h2>Contact Information</h2>

  <ul>
    <li><strong>Name:</strong> Rahul Bhole</li>
    <li><strong>Email:</strong> <a href="mailto:rahulbhole1230@gmail.com">rahulbhole1230@gmail.com</a></li>
  </ul>

</body>

</html>
