# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project performs **customer segmentation** using K-Means clustering.
The goal is to group customers based on their **income, age, and spending behavior** to help businesses make better marketing decisions.

---

## 📊 Dataset

* Dataset: Mall Customers (synthetic/generated)
* Features used:

  * Gender
  * Age
  * Annual Income (k$)
  * Spending Score (1–100)

---

## ⚙️ Steps Performed

### 1. Data Preprocessing

* Removed unnecessary column (`CustomerID`)
* Converted categorical data (`Gender`) into numerical values

### 2. Feature Scaling

* Applied **StandardScaler** to normalize data

### 3. Elbow Method

* Used to determine optimal number of clusters (k)
* Selected **k = 5**

### 4. K-Means Clustering

* Applied K-Means algorithm
* Assigned cluster labels to each customer

### 5. Visualization

* Plotted clusters using Income vs Spending Score
* Used color coding to distinguish segments

---

## 📈 Results

Customers were divided into **5 segments**:

### 🟢 Cluster 0 – High Value Customers

* High income, high spending
* Strategy: Loyalty programs, VIP offers

### 🔵 Cluster 1 – Potential Customers

* High income, low spending
* Strategy: Targeted promotions

### 🟡 Cluster 2 – Budget Customers

* Low income, high spending
* Strategy: Discounts and offers

### 🔴 Cluster 3 – Low Value Customers

* Low income, low spending
* Strategy: Minimal marketing

### 🟣 Cluster 4 – Average Customers

* متوسط income and spending
* Strategy: Retention campaigns

---

## 📁 Output

* Final dataset saved as: `customer_segments.csv`
* Includes cluster labels for each customer

---

## 🧠 Conclusion

K-Means clustering successfully segmented customers into meaningful groups.
This helps businesses:

* Understand customer behavior
* Improve marketing strategies
* Optimize resource allocation

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 🚀 Future Improvements

* Use real-world dataset
* Apply PCA for better visualization
* Compare with other clustering algorithms

---

## 👤 Author

kumbha jyothika
