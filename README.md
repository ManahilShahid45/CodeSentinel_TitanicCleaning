# 🚢 Titanic Data Cleaner & Visualizer

A data cleaning and visualization project using the famous Titanic dataset. This project focuses on handling missing data, converting categorical features to numeric, and visualizing survival trends based on gender and class.

---

## 🎯 Objective of the Task

The goal of this project is to **clean and visualize the Titanic dataset** to better understand survival patterns. This includes:
- Handling missing values appropriately
- Encoding categorical variables
- Visualizing survival rates with respect to gender and passenger class

---

## 🧰 Tools & Libraries Used

- **Python 3**
- **pandas** – for data manipulation and cleaning
- **matplotlib** – for basic plotting
- **seaborn** – for advanced visualizations

---

## 🧪 Methodology / Approach

1. **Data Cleaning**:
   - Filled or dropped missing values in key columns
   - Converted non-numeric columns like `Sex` and `Pclass` into numeric formats

2. **Exploratory Data Analysis**:
   - Explored basic survival statistics
   - Analyzed the relationship between survival and:
     - Gender
     - Passenger Class (Pclass)

3. **Visualization**:
   - Plotted survival rates using bar charts
   - Compared trends across groups using `seaborn`

---

## 📁 Dataset

- The project uses the **Titanic dataset** (`titanic.csv`)
- Must include columns like `Survived`, `Sex`, and `Pclass`
- You can download it from [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

---

## 📈 Key Insights / Results

- **Females had a significantly higher survival rate** than males
- **First-class passengers were more likely to survive**
- Combining both gender and class gave the clearest patterns

---

## 💡 Skills Gained

- Data cleaning with pandas
- Feature encoding (categorical → numeric)
- Visualizing group-based statistics with seaborn
- Reading and manipulating real-world datasets

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
jupyter notebook CodeSentinel_Task02.ipynb
