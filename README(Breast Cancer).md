# Data Analysis Project

This project demonstrates basic **data analysis and visualization** using Python libraries such as **Pandas, NumPy, Matplotlib, and Seaborn**.  
It is implemented in a Jupyter Notebook (`.ipynb` file).

---

## 📂 Project Structure
```
├── notebook.ipynb     # Main Jupyter Notebook
├── data.csv           # Input dataset (uploaded by user)
├── README.md          # Project documentation
```

---

## ⚙️ Requirements

Make sure you have the following Python packages installed:

- pandas
- numpy
- matplotlib
- seaborn
- jupyter

Install them with:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

---

## 🚀 How to Run the Project

1. **Clone or download** the project files.  
2. Place your dataset in the project folder and rename it to **`data.csv`**.  
3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Run the notebook step by step:
   - Import libraries  
   - Upload dataset  
   - Explore data (`head()`, `info()`, `describe()`)  
   - Generate plots with Matplotlib & Seaborn  

---

## 📊 Features

- Upload and read CSV data  
- Perform exploratory data analysis (EDA)  
- Summarize dataset with descriptive statistics  
- Create visualizations with Matplotlib and Seaborn  

---

## 📝 Notes

- The dataset file must be named **`data.csv`** unless modified in the code.  
- This project is designed for learning **basic data analysis workflows**.  

---

## 📌 Example Usage

```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

# Load dataset
data = pd.read_csv("data.csv")

# Display summary
print(data.info())
print(data.describe())

# Plot example
sns.histplot(data['column_name'])
plt.show()
```

---
