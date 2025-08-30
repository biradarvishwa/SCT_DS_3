# Bank Marketing Prediction using Decision Tree

This project uses the **Bank Marketing Dataset** from [Moro et al., 2011] to predict whether a bank client will subscribe to a term deposit.  
The dataset contains information from direct marketing campaigns (phone calls) carried out by a Portuguese bank.

---

##  Dataset

Two CSV files are provided:  
- **bank-full.csv** → Full dataset with 45,211 records.  
- **bank.csv** → 10% sample (4,521 records) for quick testing.  
- **bank-names.txt** → Metadata and attribute information.

**Target variable:**  
- `y`: Whether the client subscribed to a term deposit (`yes` or `no`).

---

##  Features

| Feature         | Description                                                                 |
|-----------------|-----------------------------------------------------------------------------|
| age             | Age of the client (numeric)                                                 |
| job             | Job type (categorical)                                                      |
| marital         | Marital status (categorical)                                                |
| education       | Education level (categorical)                                               |
| default         | Has credit in default? (yes/no)                                             |
| balance         | Average yearly balance in euros (numeric)                                   |
| housing         | Has housing loan? (yes/no)                                                  |
| loan            | Has personal loan? (yes/no)                                                 |
| contact         | Contact communication type (categorical)                                    |
| day             | Last contact day of the month (numeric)                                     |
| month           | Last contact month of year (categorical)                                    |
| duration        | Last contact duration in seconds (numeric)                                  |
| campaign        | Number of contacts during this campaign (numeric)                          |
| pdays           | Days passed after last contact from a previous campaign (numeric, -1 = none)|
| previous        | Number of contacts performed before this campaign (numeric)                 |
| poutcome        | Outcome of the previous marketing campaign (categorical)                   |
| y               | **Target**: Client subscribed to a term deposit? (yes/no)                   |

---

 Installation & Setup

Clone this repository:
```bash
git clone https://github.com/yourusername/bank-marketing-decision-tree.git
cd bank-marketing-decision-tree

📊 Model Overview

Algorithm: Decision Tree Classifier (Entropy Criterion)

Depth: Max depth set to 5 for interpretability

Output: Binary classification (yes or no)
