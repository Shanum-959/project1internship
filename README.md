# 🧹 DecodeLabs Internship - Project 1
## Data Cleaning & Preparation using Python (Pandas)

This repository contains my submission for **Project 1** of the **DecodeLabs Data Analytics Internship**.

## 📌 Project Objective

The objective of this project is to clean and prepare a raw dataset by identifying and fixing common data quality issues such as:

- Missing Values
- Duplicate Records
- Incorrect Date Formats
- Data Validation

---

## 🛠️ Tools & Technologies

- Python 3
- Pandas
- Google Colab
- GitHub

---

## 📂 Dataset

The dataset contains order information with the following columns:

- OrderID
- Date
- CustomerID
- Product
- Quantity
- UnitPrice
- ShippingAddress
- PaymentMethod
- OrderStatus
- TrackingNumber
- ItemsInCart
- CouponCode
- ReferralSource
- TotalPrice

---

## ✅ Data Cleaning Steps Performed

### 1. Imported Required Library
- Imported the Pandas library.

### 2. Loaded Dataset
- Loaded the CSV dataset into a Pandas DataFrame.

### 3. Data Exploration
- Displayed the first five rows.
- Checked dataset shape.
- Viewed dataset information.
- Generated statistical summary.

### 4. Missing Value Analysis
- Identified missing values.
- Calculated missing value percentage.

### 5. Missing Value Handling
- Filled missing values in the **CouponCode** column with **"No Coupon"**.

### 6. Duplicate Check
- Verified duplicate rows.
- Verified duplicate Order IDs.

### 7. Date Formatting
- Converted the Date column to datetime format.
- Verified that there were no invalid dates.

### 8. Data Type Validation
- Checked all column data types.

### 9. Data Quality Validation
- Verified that:

```
TotalPrice = Quantity × UnitPrice
```

### 10. Saved Clean Dataset
- Exported the cleaned dataset as a new CSV file.

---

## 📊 Final Validation Results

| Validation | Status |
|------------|--------|
| Missing Values | ✅ Resolved |
| Duplicate Rows | ✅ 0 |
| Duplicate Order IDs | ✅ 0 |
| Invalid Dates | ✅ 0 |
| Data Types | ✅ Correct |
| Total Price Validation | ✅ Passed |

---

## 📁 Repository Contents

```
project1internship/
│
├── data.csv
├── Cleaned_Orders_Dataset.csv
├── internship_pro1.ipynb
└── README.md
```

---

## 🎯 Learning Outcomes

Through this project, I learned:

- Data Cleaning
- Data Validation
- Handling Missing Values
- Duplicate Detection
- Date Formatting
- Data Quality Checking
- Working with Pandas
- GitHub Project Management

---

## 👩‍💻 Author

**Shanum Shahzad**

Data Science & Machine Learning Student

DecodeLabs Data Analytics Internship
