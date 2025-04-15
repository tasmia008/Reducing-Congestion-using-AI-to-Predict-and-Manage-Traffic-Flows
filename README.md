<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Reducing Congestion using AI to Predict and Manage Traffic Flows</title>
  <style>
    table {
      border-collapse: collapse;
      width: 100%;
      margin-top: 20px;
    }
    th, td {
      border: 1px solid #333;
      padding: 8px;
      text-align: center;
    }
    th {
      background-color: #f2f2f2;
    }
  </style>
</head>
<body>

  <h2>Project Overview</h2>
  <p>This project proposes an AI-driven approach to reducing urban traffic congestion by predicting traffic flows and recommending dynamic signal timings. The solution uses various machine learning algorithms and compares the impact of balanced and imbalanced datasets on prediction accuracy.</p>

  <h2>Dataset</h2>
  <p>The dataset used is a publicly available traffic flow dataset from <strong>Kaggle</strong>, collected at <strong>Kabul and Abdul-Haq Crossroads</strong> in Afghanistan. It consists of <strong>8,928 records</strong>, updated every 15 minutes, and includes both numerical and categorical variables.</p>

  <h2>Key Findings</h2>
  <ul>
    <li><strong>Best Model:</strong> XGBoost</li>
    <li><strong>Accuracy:</strong> 99.92%</li>
    <li><strong>F1 Score:</strong> 0.9992</li>
  </ul>

  <h3>Performance Comparison Table</h3>
  <table>
    <thead>
      <tr>
        <th>Model</th>
        <th>Accuracy</th>
        <th>Precision</th>
        <th>Recall</th>
        <th>F1-Score</th>
      </tr>
    </thead>
    <tbody>
      <tr><td>Logistic Regression</td><td>0.8742</td><td>0.8734</td><td>0.8742</td><td>0.8736</td></tr>
      <tr><td>Random Forest</td><td>0.9660</td><td>0.9661</td><td>0.9660</td><td>0.9659</td></tr>
      <tr><td>SVC</td><td>0.7699</td><td>0.7736</td><td>0.7699</td><td>0.7315</td></tr>
      <tr><td>XGBoost</td><td><strong>0.9992</strong></td><td><strong>0.9992</strong></td><td><strong>0.9992</strong></td><td><strong>0.9992</strong></td></tr>
      <tr><td>AdaBoost</td><td>0.7947</td><td>0.8369</td><td>0.7947</td><td>0.7378</td></tr>
      <tr><td>Gradient Boosting</td><td>0.9985</td><td>0.9985</td><td>0.9985</td><td>0.9985</td></tr>
      <tr><td>Decision Tree</td><td>0.9962</td><td>0.9962</td><td>0.9962</td><td>0.9962</td></tr>
      <tr><td>KNeighbors</td><td>0.7542</td><td>0.7417</td><td>0.7542</td><td>0.7412</td></tr>
      <tr><td>CatBoost</td><td>0.9985</td><td>0.9985</td><td>0.9985</td><td>0.9985</td></tr>
    </tbody>
  </table>

</body>
</html>

