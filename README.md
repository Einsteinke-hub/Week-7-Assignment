# 🌸 Iris Dataset Analysis

**A comprehensive data analysis and visualization project using the classic Iris dataset.**

---

## 📊 Project Overview

This repository contains an in-depth analysis of the famous Iris dataset using Python’s powerful data analysis and visualization libraries.  
The assignment demonstrates skills in **data loading**, **exploration**, **analysis**, and **visualization**.

---

## 📚 Dataset Information

- **Samples:** 150 iris flowers  
- **Species:**
  - *Setosa*
  - *Versicolor*
  - *Virginica*
- **Features (per flower):**
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)

---

## 🗂️ Project Structure

```
iris-analysis/
├── Iris_Dataset_Analysis.ipynb   # Main Jupyter notebook
├── requirements.txt              # Python dependencies
├── iris_visualizations.png       # Generated visualizations
└── README.md                     # Project documentation
```

---

## ⚙️ Requirements

- Python 3.6+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

---

## 🚀 Installation

**Clone the repository:**
```bash
git clone <repository-url>
cd iris-analysis
```

**Install dependencies:**
```bash
pip install -r requirements.txt
```
*Or manually:*
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

---

## ▶️ How to Run the Analysis

1. **Open a terminal/command prompt**
2. **Navigate to the project directory**
3. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
4. **In the web interface, open `Iris_Dataset_Analysis.ipynb`**
5. **Run the cells in order (Cell > Run All or Shift + Enter)**

---

## 📝 Assignment Tasks Completed

### 1️⃣ Load and Explore the Dataset
- Loaded Iris dataset with scikit-learn
- Displayed sample rows
- Explored structure & data types
- Checked for missing values (none found)

### 2️⃣ Basic Data Analysis
- Computed statistics for numerical columns
- Grouped by species and calculated means
- Identified patterns & differences

### 3️⃣ Data Visualization
- **Line chart:** Measurement trends across species
- **Bar chart:** Average petal length by species
- **Histogram:** Sepal length distribution
- **Scatter plot:** Sepal vs. petal length relationship

---

## 📈 Key Findings

- **Species Differences:**  
  Setosa (smallest), Virginica (largest), Versicolor (intermediate)
- **Measurement Patterns:**  
  - Strong positive correlation between petal length & width
  - Sepal length and petal length are positively correlated
  - Setosa is easily distinguishable by petal measurements
- **Data Quality:**  
  - No missing values  
  - All measurements are numerical and correctly typed

---

## 📦 Files Included

- `Iris_Dataset_Analysis.ipynb` — Main analysis notebook
- `iris_visualizations.png` — Combined visualizations
- `requirements.txt` — Python dependencies
- `README.md` — Project documentation

---

## 💡 Additional Notes

- Includes `try-except` blocks for robust error handling
- Visualizations have clear titles, labels, and legends
- The analysis follows data exploration and visualization best practices

---

> **Happy Analyzing!**  
> For questions or suggestions, feel free to open an issue or submit a pull request.
