# 🛒 E-Commerce Customer Analytics Project
### IBM SkillsBuild Data Analytics with AI Internship
**Author:** Suptashree Rout

---

## 📋 Project Overview

This project performs a comprehensive **Data Analytics and AI** study on an e-commerce customer dataset containing **25,001 records** across 10 features. The goal is to uncover actionable business insights about customer demographics, geographic distribution, and customer segmentation using Python-based data analysis and machine learning techniques.

---

## 📁 Project Structure

```
ibm project/
│
├── customer_master-selected-columns.csv         # Raw dataset
├── Suptashree Rout_Ecommerce Data Analytics Project.ipynb  # Main Jupyter Notebook
├── Suptashree Rout_ProjectReport.docx           # Professional project report
├── requirements.txt                             # Python dependencies
└── README.md                                    # Project documentation (this file)
```

---

## 📊 Dataset Description

| Column | Description |
|---|---|
| `customer_id` | Unique customer identifier (e.g., CUST-000001) |
| `customer_name` | Full name of the customer |
| `customer_age` | Age of the customer (numeric) |
| `gender` | Gender of the customer (Male / Female) |
| `customer_segment` | Market segment: Consumer, VIP, Premium, Business |
| `customer_city` | City of residence |
| `customer_state` | State or province |
| `customer_country` | Country of residence |
| `region` | Geographic region (North, South, East, West, Central) |
| `customer_postal_code` | Postal/ZIP code |

**Total Records:** 25,001  
**Countries Covered:** USA, Germany, UK, UAE, India, Canada, and more

---

## 🔍 Analysis Performed

### 1. Data Loading & Exploration
- Dataset shape, data types, and basic statistics
- Null value detection and data quality check

### 2. Univariate Analysis
- Age distribution of customers (histogram + KDE)
- Gender distribution (count plot)
- Customer segment distribution (bar chart)

### 3. Geographic Analysis
- Top 10 countries by customer count
- Top 10 states by customer count
- Regional distribution of customers

### 4. Bivariate & Multivariate Analysis
- Age distribution by customer segment (box plot)
- Gender distribution across customer segments (stacked bar)
- Regional distribution by segment (heatmap)

### 5. Customer Segmentation using K-Means Clustering
- Feature engineering (age encoding + gender encoding)
- Elbow method to find optimal clusters
- K-Means clustering with 4 clusters
- Cluster profile visualization

### 6. AI Insights & Business Recommendations
- Segment-level behavioral insights
- Data-driven business recommendations

---

## 🚀 How to Run

### Prerequisites
- Python 3.9 or above
- pip package manager

### Step 1: Install dependencies
```bash
pip install -r requirements.txt
```

### Step 2: Launch Jupyter Notebook
```bash
jupyter notebook "Suptashree Rout_Ecommerce Data Analytics Project.ipynb"
```

### Step 3: Run all cells
In the notebook, go to **Kernel → Restart & Run All** to execute the complete analysis.

---

## 🛠️ Technologies Used

| Tool | Purpose |
|---|---|
| Python 3.x | Core programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computing |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| Scikit-learn | K-Means clustering (AI/ML) |
| Jupyter Notebook | Interactive analysis environment |

---

## 📈 Key Findings

- **Consumer** segment dominates with ~50% of all customers
- **USA** is the largest customer base, followed by Germany and UK
- **VIP and Premium** customers tend to skew slightly older (35–55 age group)
- **K-Means clustering** reveals 4 distinct customer groups based on age and segment
- **Female customers** slightly outnumber male customers across most segments

---

## 👩‍💻 Author

**Suptashree Rout**  
IBM SkillsBuild Data Analytics with AI Internship  

---

## 📄 License

This project is created for educational purposes as part of the IBM SkillsBuild Internship Program.
