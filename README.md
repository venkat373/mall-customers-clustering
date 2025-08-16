# Mall Customers Clustering (K-Means)

## 📌 Project Overview
This project applies **K-Means clustering** to the `Mall_Customers.csv` dataset to group customers based on their characteristics.  
The main objective is to identify meaningful customer segments that could be useful for targeted marketing strategies.

---

## 📂 Dataset
- **File**: `Mall_Customers.csv`  
- **Columns**:
  - `CustomerID`: Unique customer identifier  
  - `Gender`: Male/Female  
  - `Age`: Customer’s age  
  - `Annual Income (k$)`: Annual income in thousands of dollars  
  - `Spending Score (1-100)`: Score assigned based on spending behavior  

---

## 🔑 Steps Performed
1. **Load and Explore Data**
   - Imported dataset using Pandas
   - Checked data types, null values, and distributions

2. **Data Preparation**
   - Selected numerical features (`Age`, `Annual Income`, `Spending Score`) for clustering
   - Applied optional **PCA** to reduce to 2D for visualization

3. **K-Means Clustering**
   - Applied K-Means with different values of `K`
   - Used **Elbow Method** to determine optimal number of clusters
   - Assigned cluster labels to customers

4. **Cluster Visualization**
   - Visualized clusters in 2D using PCA projection
   - Color-coded clusters for clarity

5. **Evaluation**
   - Calculated **Silhouette Score** to measure clustering quality

---

## 📊 Results
- **Optimal K**: Determined via Elbow Method  
- **Silhouette Score**: Indicates the quality of clustering (closer to 1 is better)  
- Clear clusters identified based on **Income** and **Spending Score**

---

## 🛠️ Technologies Used
- Python 3.x  
- Libraries:  
  - `pandas`, `numpy` (data handling)  
  - `matplotlib`, `seaborn` (visualization)  
  - `sklearn` (KMeans, PCA, metrics)

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/mall-customers-clustering.git
   cd mall-customers-clustering
