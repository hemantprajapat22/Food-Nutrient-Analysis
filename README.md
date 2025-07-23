# 🥗 Food Nutrient Analysis using USDA JSON Dataset

This project analyzes food nutrient data provided by the **US Department of Agriculture (USDA)** and made available in JSON format by developer **Ashley Williams**. The aim is to extract, clean, and analyze nutritional content across various food items using data science techniques.

---

## 📂 Dataset Information

- **Source**: [USDA FoodData Central](https://fdc.nal.usda.gov/)
- **Format**: JSON
- **Shared by**: Hemu
- **Contents**: Nutritional information of thousands of food items including proteins, fats, vitamins, minerals, and more.

---

## 🎯 Project Objectives

- Load and parse nested JSON food nutrient data
- Extract and clean relevant nutrition details
- Analyze nutritional composition of foods
- Identify top food sources for specific nutrients
- Visualize findings using graphs and plots

---

## 🧰 Tools & Technologies Used

- **Python**
- `pandas` – data manipulation  
- `json` – parsing JSON  
- `matplotlib` / `seaborn` – data visualization  
- `numpy` – numerical operations  
- *(Optional)* `streamlit` – for interactive UI

---

## 📊 Features & Steps

1. Load raw JSON dataset
2. Normalize nested structures into tabular format
3. Clean and filter nutritional values
4. Perform Exploratory Data Analysis (EDA)
5. Visualize top food sources for nutrients like:
   - Protein
   - Iron
   - Vitamin C
   - Calcium
6. *(Optional)* Create a nutrient-based food search app

---

## 📈 Sample Output

Here are some insights we can generate:
- Top 10 foods rich in protein
- Vitamin C content by food category
- Histogram of calorie distribution

---

## 🛠️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/hemantprajapat22/Food-Nutrient-Analysis.git
   cd Food-Nutrient-Analysis
