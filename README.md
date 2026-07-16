# 🏃 Ultra Marathon Data Analysis

![Project Cover](images/project_cover.png)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Ultra Marathon Running** dataset using **Python** in **Jupyter Notebook**. The analysis focuses on understanding race participation, athlete performance, race lengths, age, gender, and average speed using data visualization techniques.

---

## 🎯 Objectives

- Clean and preprocess the dataset
- Explore race participation trends
- Compare race lengths (50 km vs 50 mi)
- Analyze athlete average speed
- Study the relationship between age, gender, and performance
- Create meaningful visualizations using Seaborn

---

## 📂 Dataset

**Source:** Kaggle

**Dataset Name:** The Big Dataset of Ultra Marathon Running

**Dataset Link:**

https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running

> **Note:** The dataset is approximately **789 MB**, so it is **not included** in this repository due to GitHub's file size limit. Please download it from the Kaggle link above.

---

## 🛠️ Technologies Used

- Python
- Pandas
- Seaborn
- Jupyter Notebook

---

## 📁 Project Structure

```text
ultra-marathon-data-analysis/
│
├── data/
├── notebooks/
│   └── Ultra_Marathon_EDA.ipynb
│
├── images/
│   ├── project_cover.png
│   ├── race_length_distribution.png
│   ├── race_length_by_gender.png
│   ├── average_speed_distribution_50mi.png
│   ├── average_speed_by_race_length_gender.png
│   └── age_vs_average_speed.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📊 Exploratory Data Analysis Workflow

1. Import required libraries
2. Load the dataset
3. Explore the dataset
4. Clean and preprocess the data
5. Filter relevant records
6. Perform Exploratory Data Analysis (EDA)
7. Visualize the results
8. Draw insights

---

## 📈 Sample Visualizations

### 1. Race Length Distribution

![Race Length Distribution](images/race_length_distribution.png)

---

### 2. Race Length by Gender

![Race Length by Gender](images/race_length_by_gender.png)

---

### 3. Athlete Average Speed Distribution (50 mi)

![Average Speed Distribution](images/average_speed_distribution_50mi.png)

---

### 4. Average Speed by Race Length and Gender

![Average Speed by Race Length and Gender](images/average_speed_by_race_length_gender.png)

---

### 5. Athlete Age vs Average Speed

![Age vs Average Speed](images/age_vs_average_speed.png)

---

## 🔍 Key Insights

- The **50 km** race has significantly more participants than the **50 mi** race.
- Male athletes participated more frequently than female athletes in both race categories.
- Most athletes have an average speed between **5 and 8 mph**.
- Athlete average speed tends to decrease gradually with increasing age.
- Performance distributions are similar across race lengths, with slight variations between genders.

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/ultra-marathon-data-analysis.git
```

### 2. Navigate to the project folder

```bash
cd ultra-marathon-data-analysis
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Open the notebook

Open

```
notebooks/Ultra_Marathon_EDA.ipynb
```

using Jupyter Notebook.

### 5. Run all cells

Execute all notebook cells to reproduce the analysis and visualizations.

---

## 📌 Future Improvements

- Perform additional exploratory analysis on countries and events
- Add more visualizations
- Compare race performance across multiple years
- Build an interactive dashboard in the future

---

## 👩‍💻 Author

**Pavithra**

Aspiring Data Analyst | Python | Pandas | Seaborn

---

⭐ If you found this project helpful, consider giving it a star!