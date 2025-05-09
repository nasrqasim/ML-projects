# ML-projects
# 🎓 LUAWMS Student Department Recommendation System

A machine learning project built with Python and Jupyter Notebook to recommend suitable departments to students of LUAWMS based on their academic background and interests.

---

## 📌 Objective

This project helps students identify the most suitable university departments by analyzing:
- Academic performance (Matric, Intermediate, Entry Test scores)
- Preferred subjects
- Interest areas

The model clusters similar students and applies recommendation rules to suggest departments such as BS Computer Science, BS Zoology, etc.

---

## 📁 Dataset

**File:** `LUAWMS_Student_Data_50.csv`

Contains:
- `Name`
- `Matric_Marks`
- `Inter_Marks`
- `Entry_Test_Score`
- `Preferred_Subject`
- `Interest_Area`

---

## 🚀 How It Works

### 🔹 Step 1: Data Preprocessing
- Clean missing values
- Label Encode categorical columns
- Normalize numerical marks (0–1 scale)

### 🔹 Step 2: Clustering
- Applied **K-Means** clustering (`n_clusters=3`)
- Grouped students with similar profiles

### 🔹 Step 3: Recommendation Logic
- Used `if-else` rules to recommend departments based on subjects and scores

### 🔹 Step 4: Output
- Displays student clusters
- Shows department recommendations
- Saves results to
