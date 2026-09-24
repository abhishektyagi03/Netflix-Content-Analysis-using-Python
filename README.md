# 🎬 Netflix Content Analysis Using Python

## 📌 Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on the Netflix titles dataset using Python.

The analysis focuses on understanding Netflix's content library, including **Movies vs TV Shows, ratings, release years, countries, and recent content trends**.

The project uses Python libraries such as **Pandas, NumPy, Matplotlib, and Seaborn** to clean, analyze, and visualize the data.

---

## 🎯 Objectives

The main objectives of this project are:

* Analyze the distribution of Movies and TV Shows.
* Understand Netflix content ratings.
* Analyze content release trends over the years.
* Identify countries producing the most Netflix content.
* Explore recently released content.
* Find the latest Movies and TV Shows based on release year.
* Perform basic data quality checks.

---

## 🛠️ Technologies Used

* 🐍 **Python**
* 🐼 **Pandas**
* 🔢 **NumPy**
* 📊 **Matplotlib**
* 📈 **Seaborn**
* 📓 **Jupyter Notebook**

---

## 📂 Dataset

The project uses the **Netflix Titles Dataset** containing information about Netflix Movies and TV Shows.

Important columns analyzed include:

* `title`
* `type`
* `director`
* `cast`
* `country`
* `release_year`
* `rating`
* `duration`
* `listed_in`
* `description`

---

## 🔍 Analysis Performed

### 1. Data Understanding

The project checks:

* Dataset shape
* Column names
* Data types
* Descriptive statistics
* Unique values
* Missing values
* Duplicate records

### 2. Movies vs TV Shows

The distribution of Netflix content is analyzed to compare the number of:

* 🎥 Movies
* 📺 TV Shows

A count plot is used for visualization.

### 3. Content Ratings

The project analyzes the frequency of different Netflix ratings and visualizes the rating distribution using a bar/count plot.

### 4. Release Year Analysis

The release years of Netflix content are analyzed to understand how the content library has changed over time.

A trend visualization is created to show the number of titles released across different years.

### 5. Recent Content Analysis

Content released from **2010 onwards** is separately analyzed to understand recent Netflix content trends.

### 6. Country Analysis

The project identifies the countries with the highest number of Netflix titles.

A visualization of the **Top 10 countries** is created.

### 7. Latest Movies

The analysis extracts recently released Movies based on their `release_year`.

### 8. Latest TV Shows

Similarly, the most recently released TV Shows are identified.

---

## 📊 Visualizations

The project includes visualizations such as:

* Movies vs TV Shows
* Netflix Content by Rating
* Netflix Content Release Trend
* Netflix Content Released Since 2010
* Top 10 Countries by Netflix Content

These visualizations make it easier to identify patterns and trends in Netflix's content library.

---

## 💡 Key Learning Outcomes

Through this project, I practiced:

* Data loading using Pandas
* Data exploration
* Data quality checking
* Handling and identifying missing values
* Duplicate detection
* Filtering and sorting data
* Value counting
* Percentage calculations
* Exploratory Data Analysis
* Data visualization
* Working with real-world datasets

---

## 📁 Project Structure

```text
Netflix-Content-Analysis/
│
├── Netflix_Content_Analysis.ipynb
├── netflix_titles.csv
└── README.md
```

---

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/abhishektyagi03/Netflix-Content-Analysis.git
```

### Step 2: Open the Project

```bash
cd Netflix-Content-Analysis
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Start Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook:

```text
Netflix_Content_Analysis.ipynb
```

### Step 5: Update Dataset Path

Make sure the CSV dataset is available in the project folder and update the file path if required.

For example:

```python
df = pd.read_csv("netflix_titles.csv")
```

---

## 📌 Future Improvements

Possible improvements for this project include:

* Create an interactive dashboard using **Power BI**
* Build an interactive dashboard using **Streamlit**
* Perform genre-level analysis
* Analyze directors and actors
* Analyze movie duration
* Perform country-wise genre analysis
* Add advanced statistical analysis
* Build a Netflix recommendation system

---

## 👨‍💻 Author

**Abhishek Tyagi**

🎓 MCA Student | Data Analyst Aspirant

### Skills

`Python` `SQL` `Excel` `Power BI` `Pandas` `NumPy` `Matplotlib` `Seaborn`

---

## ⭐ If you Like This Project

If you find this project useful, consider giving the repository a ⭐ on GitHub.

---

## 📜 License

This project is created for **educational and portfolio purposes**.
