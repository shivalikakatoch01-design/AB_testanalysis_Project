\# A/B Test Analysis — Landing Page Conversion



\## Overview

I analyzed an e-commerce A/B test to determine whether a new landing page leads to a statistically significant increase in conversions.



\## Dataset

The dataset (`ab\_data.csv`) is included in this repo.



\*\*Original source:\*\* https://www.kaggle.com/datasets/zhangluyuan/ab-testing



\## Tools \& Libraries Used

\- Python

\- pandas

\- matplotlib / seaborn

\- scipy / statsmodels

\- Jupyter Notebook



\## Key Insights

\- Control conversion rate: 12.04%, Treatment: 11.89% — treatment performed slightly worse

\- p-value: 0.2161 — result is NOT statistically significant

\- Chi-square test confirmed the same result

\- Weekend vs weekday traffic showed no meaningful confounder effect

\- Statistical power was only 0.23 — the test was underpowered for this effect size

\- \*\*Recommendation: Do not roll out the new landing page\*\*



\## Visualizations

!\[Conversion Rate by Group](images/conversion\_rate.png)

!\[Converted Count](images/converted\_count.png)

!\[Page Conversion](images/page\_conversion.png)

!\[Group Heatmap](images/group\_heatmap.png)

!\[Confidence Interval Plot](images/ci\_plot.png)



\## How to Run

1\. Clone this repository

2\. Open `ab\_test\_analysis.ipynb` in Jupyter Notebook

3\. Run all cells



\## Author

Shivalika Katoch



\[LinkedIn](https://www.linkedin.com/in/shivalika-katoch-da)



\[GitHub](https://github.com/shivalikakatoch01-design)

