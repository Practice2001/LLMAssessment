# Sentiment Analysis & Predictive Modeling for Workplace Engagement

## Overview
This project analyzes employee communications to assess **sentiment trends, flight risk, and predictive modeling accuracy**. The insights guide **HR strategies, engagement initiatives, and retention planning** through **data-driven sentiment classification**.

---

## Key Findings

### **Top 3 Positive Employees**
**johnny.palmer@enron.com** – Frequently ranked, achieving **high sentiment scores** (max: **6**).  
**eric.bass@enron.com** – Consistently appeared in top rankings, reaching **max sentiment: 5**.  
**lydia.delgado@enron.com** – Regularly ranked with **strong positive sentiment**, peaking at **5**.

### **Top 3 Negative Employees**
**eric.bass@enron.com** – Frequently flagged for **negative sentiment**, reaching **-12 in May 2011**.  
**kayne.coulter@enron.com** – Regularly appeared with **high negative sentiment**, peaking at **-9** in April 2011.  
**bobette.riner@ipgdirect.com** – Consistently flagged for negative sentiment, reaching **-5 in multiple months**.

---

## Employees Flagged as Flight Risks
Employees with **high negative sentiment counts** over **rolling 30-day windows**:

| Employee Email               | Negative Email Count (30 Days) |
|------------------------------|------------------------------:|
| bobette.riner@ipgdirect.com  | 11  |
| don.baughman@enron.com       | 16  |
| eric.bass@enron.com          | 16  |
| john.arnold@enron.com        | 14  |
| johnny.palmer@enron.com      | 12  |
| kayne.coulter@enron.com      | 17  |
| lydia.delgado@enron.com      | 14  |
| patti.thompson@enron.com     | 14  |
| rhonda.denton@enron.com      | 12  |
| sally.beck@enron.com         | 12  |

---

## Key Insights
**Sentiment Distribution Trends** – Negative sentiment slightly outweighs positive sentiment, signaling **moderate workplace dissatisfaction**. Expanding dataset coverage across all departments would improve **accuracy**.  
**Employee Flight Risk Detection** – Employees with **high negative sentiment scores** are flagged for **potential disengagement**, allowing early **HR intervention**.  
**Department Bias in Analysis** – IT, HR, and Marketing dominate the dataset. Including **Finance, Sales, and Operations** could **enhance organizational sentiment insights**.  
**Predictive Modeling Effectiveness** – Machine learning models like **BERT, LLaMA 2, and linear regression** accurately forecast **sentiment trends and flight risk probabilities**.  
**Model Performance Insights** – Error distribution suggests **potential overfitting**; refining **feature selection and alternative NLP models** could improve prediction **accuracy**.

---

## Recommendations
**Expand Dataset Coverage** – Include more employee communications from **underrepresented departments** for **better sentiment tracking**.  
**Enhance Predictive Accuracy** – Fine-tune **BERT or LLaMA 2** for **workplace-specific sentiment classification improvements**.  
**Implement Targeted HR Interventions** – Leverage **flight risk predictions** to improve **employee wellness programs and engagement strategies**.  
**Optimize Model Workflows with TorchScript** – Implement **Torch tracing** for **execution tracking and sentiment classification efficiency**.  
**Improve Sentiment Classification with Advanced Features** – Utilize **time-series modeling, engagement frequency tracking, and department-level insights** for **accurate sentiment forecasting**.

---

## Conclusion
This project establishes a **strong foundation** for **workplace sentiment analysis**, enabling organizations to drive **employee engagement, retention, and satisfaction through data-driven insights**.  

---
