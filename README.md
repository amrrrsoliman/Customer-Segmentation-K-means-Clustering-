# 🛍️ Mall Customer Segmentation using K-Means

This project applies **K-Means clustering** to segment mall customers based on their **annual income** and **spending score**.  
The goal is to help businesses understand customer groups and create better marketing strategies.

---

## 📂 Dataset
- **Source:** [Mall Customer Segmentation Dataset (Kaggle)](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Features used:**
  - `Annual Income (k$)`: Customers' annual income in thousand dollars.
  - `Spending Score (1-100)`: A score assigned by the mall based on customer spending behavior.

---

## 🧾 Project Workflow

1. **Data Exploration & Cleaning**  
   - Checked dataset structure, null values, and data types.

2. **Feature Selection & Scaling**  
   - Used only `Annual Income` and `Spending Score`.
   - Applied `StandardScaler` to bring features to the same scale.

3. **Choosing Optimal K (Clusters)**  
   - Used **Elbow Method** and **Silhouette Analysis** to determine the best number of clusters.

4. **K-Means Clustering**  
   - Applied K-Means with chosen `k` to segment customers.

5. **Visualization**  
   - Created **2D scatter plots** to visualize customer segments.

---

## 🔍 Key Insights
- Customers were successfully grouped into meaningful clusters based on spending habits and income levels.
- These clusters can guide targeted marketing and promotions.

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 📜 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/mall-customer-segmentation.git
