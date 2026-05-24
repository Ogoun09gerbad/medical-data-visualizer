
```markdown
# Medical Data Visualizer

This project is part of the freeCodeCamp Data Analysis with Python certification.

It analyzes and visualizes medical examination data using Python, Pandas, Matplotlib, Seaborn, and NumPy.

---

## 📊 Dataset

The dataset used in this project is a medical examination dataset provided by freeCodeCamp.

It contains information about patients such as:
- age
- height
- weight
- blood pressure
- cholesterol and glucose levels
- lifestyle habits (smoking, alcohol, physical activity)
- cardiovascular disease status

---

## 🎯 Project Objectives

The goal of this project is to create two visualizations:

### 1. Categorical Plot
A bar chart showing the counts of:
- cholesterol
- glucose
- smoking
- alcohol consumption
- physical activity
- overweight status

The data is split by cardiovascular disease status (`cardio = 0` and `cardio = 1`).

---

### 2. Heatmap
A correlation matrix showing relationships between medical features after cleaning the dataset by:
- removing incorrect blood pressure values
- removing extreme values for height and weight (based on percentiles)

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📁 Project Structure

```

medical-data-visualizer/
│── medical_data_visualizer.py
│── main.py
│── test_module.py
│── medical_examination.csv
│── README.md

````

---

## 🚀 How to Run the Project

### Install dependencies
```bash
pip install pandas numpy matplotlib seaborn
````

### Run the program

```bash
python main.py
```

---

## 📈 Expected Output

* A categorical bar plot showing health indicators by cardiovascular disease status
* A correlation heatmap of medical features

---

## 🧠 Skills Learned

* Data cleaning and preprocessing
* Feature engineering (BMI calculation, overweight classification)
* Data normalization
* Data visualization with Seaborn and Matplotlib
* Correlation analysis

---

## 👨‍💻 Author

This project was completed as part of the freeCodeCamp Data Analysis with Python certification.

---

## 📜 License

This project is for educational purposes only.

```

---
