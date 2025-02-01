# ecommerce-transaction-dataset

## **Project Overview**
This project focuses on **customer segmentation and similarity modeling** using an **eCommerce Transactions Dataset**. The assignment consists of three major tasks:

1. **Exploratory Data Analysis (EDA)** - Understanding the data and deriving business insights.
2. **Lookalike Model** - Identifying similar customers based on profile and transaction history.
3. **Customer Segmentation (Clustering)** - Grouping customers using machine learning techniques.

---

## **Dataset Description**
The dataset consists of three CSV files:
- **Customers.csv** → Contains customer information (ID, Name, Region, Signup Date).
- **Products.csv** → Contains product details (ID, Name, Category, Price).
- **Transactions.csv** → Contains transaction history (Transaction ID, Customer ID, Product ID, Quantity, Total Value, Price).

---

## **Tasks & Implementation**
### **1️⃣ Exploratory Data Analysis (EDA)**
- Performed data cleaning, handling missing values, and visualizing key trends.
- Identified **business insights** such as revenue distribution, frequent buyers, and region-based trends.
- Deliverables:
  - 📂 `EDA.ipynb` (Jupyter Notebook with EDA analysis)
  - 📄 `EDA_Report.pdf` (Summary of business insights)

### **2️⃣ Lookalike Model**
- Used **Nearest Neighbors Algorithm** to find the top 3 most similar customers for each user.
- Considered both **customer profile** and **transaction history**.
- Saved the lookalike recommendations in **Lookalike.csv**.
- Deliverables:
  - 📂 `Lookalike_Model.ipynb`
  - 📄 `Lookalike.csv` (Mapping of customers to their top 3 lookalikes)

### **3️⃣ Customer Segmentation (Clustering)**
- Applied **K-Means Clustering** to segment customers based on **spending behavior**.
- Evaluated clusters using **Davies-Bouldin Index (DB Index)** and visualized results.
- Deliverables:
  - 📂 `Customer_Segmentation.ipynb`
  - 📄 `Clustering_Report.pdf`
  - 📄 `Customer_Segments.csv` (Final segmented customer data)

---

## **Installation & Usage**
### **Requirements**
- Python 3.x
- Jupyter Notebook
- Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib

### **Run the Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation.git
   cd customer-segmentation
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter Notebooks:
   ```bash
   jupyter notebook
   ```

---

## **Results & Insights**
- The **Lookalike Model** successfully identifies similar customers for better marketing.
- The **Clustering Model** segments customers effectively, helping in **targeted promotions**.
- Business insights help in understanding revenue distribution, customer spending behavior, and product preferences.

---

## **Project Structure**
📁 `data/` → Contains raw dataset files (Customers.csv, Products.csv, Transactions.csv)  
📂 `EDA.ipynb` → Exploratory Data Analysis script  
📂 `Lookalike_Model.ipynb` → Lookalike model implementation  
📂 `Customer_Segmentation.ipynb` → Clustering analysis  
📄 `Lookalike.csv` → Lookalike recommendations  
📄 `Customer_Segments.csv` → Final customer clusters  
📄 `EDA_Report.pdf` → Business insights from EDA  
📄 `Clustering_Report.pdf` → Clustering results summary  
📄 `README.md` → Project documentation (this file)  

---

## **Contributors**
- **Somesh-Gowda** 

---

## **License**
This project is licensed under the **MIT License**.

