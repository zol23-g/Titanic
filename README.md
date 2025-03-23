
# Titanic EDA - Exploratory Data Analysis

This project performs a basic exploratory data analysis (EDA) on the Titanic dataset using the version provided by **Seaborn**. The goal is to understand the structure, relationships, and patterns within the dataset and to prepare it for future modeling tasks such as classification.

---

## 📦 Dataset

The dataset is loaded via `seaborn`:

```python
import seaborn as sns
df = sns.load_dataset('titanic')
```

It includes information on passengers aboard the Titanic, such as:

- `survived`: Survival (0 = No; 1 = Yes)
- `pclass`: Ticket class (1 = 1st; 2 = 2nd; 3 = 3rd)
- `sex`: Gender
- `age`: Age in years
- `sibsp`: # of siblings / spouses aboard
- `parch`: # of parents / children aboard
- `fare`: Passenger fare
- `embarked`: Port of Embarkation
- `class`, `who`, `deck`, `embark_town`, `alive`, `alone` (derived features)

---

