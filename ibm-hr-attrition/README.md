# IBM HR Attrition Dashboard

A four-page Power BI dashboard analysing why employees leave, built on the IBM HR Analytics Employee Attrition & Performance dataset.

> The dataset is fictional, created by IBM data scientists for practice. Findings describe this dataset, not a real company.

## Business question

Which factors are linked to employee attrition, and where should HR focus retention efforts first?

## Dataset

- 1,470 employees, 35 columns
- Source: [IBM HR Analytics Employee Attrition & Performance (Kaggle)](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- File: [`data/WA_Fn-UseC_-HR-Employee-Attrition.csv`](data/WA_Fn-UseC_-HR-Employee-Attrition.csv)

## Dashboard pages

1. **Executive Overview**: headcount, attrition rate (16.1%), and attrition by department, job role, age group, marital status and gender.
2. **Root Cause Analysis**: overtime, business travel, work-life balance, job and environment satisfaction, tenure, and job involvement.
3. **Compensation & Fairness**: income of leavers vs stayers, income by job level, prior companies, and stock option level.
4. **Retention Strategy & Risk Profiling**: a five-factor risk score, attrition by job level and overtime, and recommendations.

## Key findings

- Employees working overtime leave at 30.5%, compared with 10.4% for those who do not.
- At Job Level 1, attrition reaches 53% with overtime, versus 16% without.
- Frequent business travellers leave at 24.9%, versus 8.0% for non-travellers.
- Low job satisfaction combined with a low-rated work environment shows 38% attrition.
- Employees without stock options leave at 24.4%. All single employees fall in this group, so marital status partly explains the gap.
- Leavers earn on average $2.05K less per month than stayers, a gap that largely reflects job level.
- 97 active employees combine overtime with low job satisfaction and are flagged as high risk.

## Recommendations

1. **Reduce overtime at entry level**: cap overtime hours and rotate workload, starting from Job Level 1.
2. **Rework business travel**: limit trips per person, rotate schedules, and give recovery days.
3. **Listen to dissatisfied employees**: short quarterly surveys and stay interviews for the lowest scores.
4. **Quick win, expand stock options**: start with employees who have none.

## Files

- [`dashboard/ibm-hr-attrition.pbix`](dashboard/ibm-hr-attrition.pbix): open with Power BI Desktop.
