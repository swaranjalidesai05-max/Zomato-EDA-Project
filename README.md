# Zomato-EDA-Project
# 🍽️ Zomato Exploratory Data Analysis (EDA)

An Exploratory Data Analysis (EDA) project on the Zomato Bangalore Restaurant dataset using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**. The project focuses on cleaning messy real-world data and extracting meaningful insights about restaurants, ratings, locations, pricing, and customer preferences.

---

## 📌 Project Overview

The objective of this project is to:

- Clean and preprocess the Zomato dataset
- Handle missing values and duplicate records
- Perform exploratory data analysis (EDA)
- Visualize restaurant trends using graphs
- Identify patterns in ratings, costs, restaurant types, and locations

---

## 📂 Dataset

The dataset contains information about restaurants listed on Zomato, including:

- Restaurant Name
- Location
- Rating
- Votes
- Online Order Availability
- Table Booking Availability
- Restaurant Type
- Cuisines
- Approximate Cost for Two
- City

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Removed unnecessary columns
  - URL
  - Address
  - Phone
  - Menu Items
  - Dish Liked
  - Reviews List
- Renamed columns for better readability
- Removed missing values
- Cleaned restaurant names
- Converted ratings into numeric values
- Converted cost column to integer format
- Removed duplicate records
- Exported cleaned dataset

---

## 📊 Exploratory Data Analysis

The project includes visualizations for:

### 1. Online Order Availability
- Count of restaurants providing online ordering.

### 2. Best Restaurant Locations
- Locations with the highest median ratings.
- Locations with the highest customer votes.

### 3. Restaurant Types
- Most common restaurant types.

### 4. Restaurant Cost Distribution
- Distribution of approximate cost for two people.

### 5. Table Booking Analysis
- Restaurants offering table booking facilities.

### 6. Restaurant Distribution by Location
- Number of restaurants across selected locations.

---

## 📈 Key Insights

- Online ordering is available in a large number of restaurants.
- Some locations consistently receive higher customer ratings.
- Casual Dining and Quick Bites are among the most common restaurant types.
- Most restaurants fall within a moderate price range.
- Table booking is less common compared to restaurants without booking facilities.

---

## 📁 Project Structure

```
Zomato-EDA/
│
├── Zomato.ipynb          # Complete EDA Notebook
├── zomato.csv            # Original Dataset
├── zomato_clean.csv      # Cleaned Dataset
├── README.md             # Project Documentation
```

---

## 🚀 How to Run

1. Clone this repository

```bash
git clone https://github.com/your-username/Zomato-EDA.git
```

2. Navigate to the project folder

```bash
cd Zomato-EDA
```

3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

4. Open the notebook

```bash
jupyter notebook
```

5. Run all cells.

---

## 📚 Learning Outcomes

Through this project, I learned:

- Data Cleaning Techniques
- Handling Missing Values
- Data Transformation
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Insight Generation

---

## 👩‍💻 Author

**Swaranjali Desai**

- B.E. Information Technology
- Python | Data Analytics | SQL | Power BI | Tableau

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub!
