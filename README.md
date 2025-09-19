<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <meta name="description" content="HR data analysis project using Python and Jupyter Notebook to explore employee attrition, performance, and workforce trends." />
  <title>HR Data Analysis Project</title>
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
      line-height: 1.6;
      color: #222;
      padding: 28px;
      max-width: 900px;
      margin: auto;
    }
    h1 {
      color: #0b5ed7;
      margin-bottom: 8px;
    }
    h2 {
      color: #0b5ed7;
      margin-top: 24px;
      border-bottom: 1px solid #ddd;
      padding-bottom: 4px;
    }
    p.lead {
      margin-top: 0;
      color: #333;
      font-size: 1.05em;
    }
    ul {
      margin: 8px 0 16px 20px;
    }
    code {
      background: #f6f8fa;
      padding: 2px 6px;
      border-radius: 6px;
      font-family: SFMono-Regular, Menlo, Monaco, Consolas, "Courier New", monospace;
    }
    .box {
      background: #fbfbfd;
      border: 1px solid #e6e9ef;
      padding: 14px;
      border-radius: 8px;
      margin-bottom: 20px;
    }
    .small {
      color: #666;
      font-size: 0.95em;
    }
    .note {
      background: #fff7e6;
      border-left: 4px solid #ffd580;
      padding: 10px 12px;
      margin: 16px 0;
      border-radius: 4px;
    }
  </style>
</head>
<body>
  <h1>HR Data Analysis Project</h1>
  <p class="lead">
    This project provides a comprehensive analysis of HR data using Python and Jupyter Notebook. 
    The objective is to explore employee attrition, performance, demographics, and salary trends 
    to help organizations make data-driven workforce decisions.
  </p>

  <div class="box">
    <strong>Description</strong>
    <p class="small">
      The analysis focuses on understanding employee behavior and identifying factors that influence
      attrition and performance. Through data cleaning, visualization, and statistical exploration, 
      the project provides actionable insights to optimize workforce management and retention strategies.
    </p>
  </div>

  <h2>Dataset Overview</h2>
  <ul>
    <li><strong>EmployeeID</strong> – Unique identifier for each employee</li>
    <li><strong>Age</strong> – Age of the employee</li>
    <li><strong>Gender</strong> – Gender of the employee</li>
    <li><strong>Department</strong> – Department name</li>
    <li><strong>JobRole</strong> – Specific role of the employee</li>
    <li><strong>Education</strong> – Level of education attained</li>
    <li><strong>Attrition</strong> – Indicates if the employee left the company (Yes/No)</li>
    <li><strong>MonthlyIncome</strong> – Salary details</li>
    <li><strong>PerformanceRating</strong> – Employee performance evaluation score</li>
    <li><strong>YearsAtCompany</strong> – Total tenure of the employee</li>
    <li><strong>OverTime</strong> – Overtime status (Yes/No)</li>
  </ul>

  <h2>Key Analysis Covered</h2>
  <ul>
    <li>Employee demographics: Age, gender, and education distribution</li>
    <li>Department and role distribution analysis</li>
    <li>Salary trends by role and department</li>
    <li>Attrition analysis and factors influencing turnover</li>
    <li>Relationship between tenure and attrition</li>
    <li>Impact of overtime on employee retention</li>
    <li>Performance ratings across departments</li>
    <li>Correlation analysis to identify key drivers of attrition</li>
  </ul>

  <h2>Tools and Libraries</h2>
  <ul>
    <li>Python (Pandas, NumPy)</li>
    <li>Jupyter Notebook</li>
    <li>Matplotlib and Seaborn for data visualization</li>
    <li>Scikit-learn (optional, for predictive modeling)</li>
  </ul>

  <h2>How to Run</h2>
  <ol>
    <li>Clone or download the repository: 
      <code>git clone https://github.com/your-username/HR-Data-Analysis.git</code>
    </li>
    <li>Open <code>Hr_data_analyse.ipynb</code> in Jupyter Notebook or VS Code.</li>
    <li>Install required libraries:
      <code>pip install pandas numpy matplotlib seaborn scikit-learn</code>
    </li>
    <li>Run the notebook step by step to reproduce the analysis and visualizations.</li>
  </ol>

  <div class="note">
    <strong>Note:</strong> For large datasets, consider integrating SQL or cloud-based databases for better performance.
  </div>

  <h2>Example Insights</h2>
  <ul>
    <li>Higher attrition rates among employees with less than two years of service.</li>
    <li>Significant correlation between overtime and attrition.</li>
    <li>Research & Development department shows both high headcount and high attrition.</li>
    <li>Performance ratings are relatively consistent across most departments.</li>
  </ul>

  <h2>License</h2>
  <p>This project is licensed under the MIT License. See the <code>LICENSE</code> file for more details.</p>

  <hr />
  <p class="small">Created to demonstrate HR analytics and data-driven workforce insights using Python.</p>
</body>
</html>
