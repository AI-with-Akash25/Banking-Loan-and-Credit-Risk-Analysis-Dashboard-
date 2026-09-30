
<div align="center">

<h1>🏦 Banking Loan & Credit Risk Analysis Dashboard</h1>

<h3>Banking Data Analysis and Credit Risk Dashboard Using Power BI</h3>

</div>

<hr>

<h2>📌 Project Overview</h2>

<p>
The <b>Banking Loan & Credit Risk Analysis Dashboard</b> is an interactive
Power BI project developed to analyze loan applications, loan portfolio
performance, customer credit scores, risk levels, and financial performance.
</p>

<p>
The dashboard contains <b>5,000 loan application records</b> and uses
interactive KPI cards, charts, slicers, and page navigation to provide
meaningful insights from banking data.
</p>

<h2>🛠️ Tools & Technologies</h2>

<ul>
<li>Microsoft Power BI</li>
<li>Power Query</li>
<li>DAX</li>
<li>Microsoft Excel</li>
<li>Data Cleaning & Transformation</li>
<li>Data Analysis</li>
<li>Data Visualization</li>
</ul>

<h2>📊 Dashboard Pages</h2>

<h3>1️⃣ Loan Portfolio Performance</h3>

<p>
Provides an overview of the bank's loan portfolio and application performance.
</p>

<b>Key KPIs:</b>

<ul>
<li>Total Loan Amount</li>
<li>Total Applications</li>
<li>Approved Loans</li>
<li>Rejected Loans</li>
<li>Average Loan Amount</li>
<li>Average DTI Ratio</li>
</ul>

<b>Visualizations:</b>

<ul>
<li>Loan Status Distribution</li>
<li>Loan Amount by Loan Type</li>
<li>Loan Application by Age Group</li>
<li>Loan Application Trend</li>
</ul>

<h3>2️⃣ Credit & Risk Analysis</h3>

<p>
Analyzes customer creditworthiness and loan risk.
</p>

<b>Key KPIs:</b>

<ul>
<li>Average Credit Score</li>
<li>Average Risk Score</li>
<li>High Risk Customers</li>
</ul>

<b>Visualizations:</b>

<ul>
<li>Risk Level Distribution</li>
<li>Credit Score vs Risk Score</li>
<li>Risk Level by Loan Type</li>
</ul>

<h3>3️⃣ Financial Performance Analysis</h3>

<p>
Analyzes financial performance using loan, income, purpose, and interest-rate
related information.
</p>

<b>Visualizations:</b>

<ul>
<li>Annual Income vs Loan Amount</li>
<li>Loan Amount by Loan Purpose</li>
<li>Interest Rate by Loan Type</li>
<li>Financial Performance Trends</li>
</ul>

<h2>📈 DAX Measures</h2>

<pre>
Total Loan Amount =
SUM(Banking_Loan[Loan_Amount])

Total Applications =
COUNTROWS(Banking_Loan)

Approved Loans =
CALCULATE(
    COUNTROWS(Banking_Loan),
    Banking_Loan[Loan_Status] = "Approved"
)

Rejected Loans =
CALCULATE(
    COUNTROWS(Banking_Loan),
    Banking_Loan[Loan_Status] = "Rejected"
)

Average Credit Score =
AVERAGE(Banking_Loan[Credit_Score])

Average Risk Score =
AVERAGE(Banking_Loan[Risk_Score])

High Risk Customers =
CALCULATE(
    COUNTROWS(Banking_Loan),
    Banking_Loan[Risk_Level] = "High"
)

Average Loan Amount =
AVERAGE(Banking_Loan[Loan_Amount])

Average DTI Ratio =
AVERAGE(Banking_Loan[DTI_Ratio])

Average Loan to Income Ratio =
AVERAGE(Banking_Loan[Loan_to_Income_Ratio])
</pre>

<h2>🎛️ Interactive Slicers</h2>

<ul>
<li>Loan Status</li>
<li>City</li>
<li>Risk Level</li>
<li>Age Group</li>
<li>Application Date</li>
<li>Employment Type</li>
</ul>

<h2>🔄 Page Navigation</h2>

<p>
The dashboard contains three interactive pages:
</p>

<p align="center">
<b>
Loan Portfolio Performance
→
Credit & Risk Analysis
→
Financial Performance Analysis
</b>
</p>

<h2>🔍 Key Insights</h2>

<ul>
<li>Analyzes overall loan portfolio performance.</li>
<li>Examines loan applications across different loan types.</li>
<li>Analyzes customer credit scores and risk scores.</li>
<li>Identifies high-risk customers.</li>
<li>Compares risk levels across loan types.</li>
<li>Analyzes loan applications by age group.</li>
<li>Provides financial performance insights.</li>
</ul>

<h2>📂 Dataset</h2>

<p>
<b>Dataset:</b> Banking Loan & Risk Analysis Dataset
</p>

<p>
<b>Total Records:</b> 5,000 Loan Applications
</p>

<ul>
<li>Customer Details</li>
<li>Loan Details</li>
<li>Loan Status</li>
<li>Credit Score</li>
<li>Risk Score</li>
<li>Risk Level</li>
<li>Loan Type</li>
<li>Loan Purpose</li>
<li>Income</li>
<li>DTI Ratio</li>
<li>Employment Type</li>
<li>Application Date</li>
<li>City</li>
</ul>

<h2>🎯 Project Objective</h2>

<p>
The objective of this project is to transform banking data into an
interactive Power BI dashboard using <b>Power Query, DAX and Power BI</b>
to analyze loan portfolio performance, customer credit risk, and financial
performance.
</p>

<h2>👨‍💻 Developed By</h2>

<p>
<b>Akash A.</b>
</p>

<p>
Power BI | DAX | Power Query | Excel | Data Analysis | Data Visualization
</p>

<hr>

<div align="center">

<h3>📊 Banking Loan & Credit Risk Analysis Dashboard</h3>

<p>
<b>Developed using Microsoft Power BI</b>
</p>

</div>
