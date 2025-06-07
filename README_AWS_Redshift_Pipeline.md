
# 🚀 AWS Redshift Data Warehouse Pipeline – by Samratha Reddy

This project is a **modern data warehouse pipeline** designed and customized by **Samratha Reddy**, focused on ingesting, transforming, and loading data into **Amazon Redshift** using **Python and AWS services**. The solution mimics real-world enterprise architecture for batch ETL processing.

**GitHub Repository:** https://github.com/samrathareddy/AWS-Redshift-Data-Warehouse-Pipeline.git 
---

## 📌 Project Highlights

- Built a scalable ETL pipeline from scratch using Python.
- Created and configured AWS Redshift clusters programmatically.
- Uploaded staging and production data from S3 to Redshift.
- Used SQL for table creation, data modeling, and analytics.
- Emulated real business use cases such as user activity logs and song metadata processing.

---

## 🛠️ Tech Stack

- **Language:** Python 3
- **Cloud:** AWS Redshift, S3, IAM
- **Libraries:** psycopg2, configparser
- **Data:** Log and song JSON files
- **Tools:** Git, Jupyter Notebook, SQL

---

## 📁 Folder Structure

```
AWS-Redshift-Pipeline/
├── create_tables.py           # Drops & creates tables in Redshift
├── etl.py                     # Loads data into staging & analytics tables
├── dwh.cfg                    # AWS Redshift and S3 configurations
├── sql_queries.py             # SQL statements for ETL process
├── README.md                  # Project overview and documentation
└── data/                      # Contains sample input files (optional)
```

---

## 🚀 Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/samrathareddy/AWS-Redshift-Pipeline.git
   cd AWS-Redshift-Pipeline
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure AWS and Redshift**
   - Edit the `dwh.cfg` file with your Redshift cluster and IAM role credentials.

4. **Run the pipeline**
   ```bash
   python create_tables.py
   python etl.py
   ```

---

## 👨‍💻 About Me – Samratha Reddy

A passionate **Data Engineer and Graduate Student at Cleveland State University**, I build robust data pipelines, streaming architectures, and cloud-based ETL systems using Python, AWS, and SQL. This project reflects my practical knowledge of Redshift-based architectures.

📬 Connect with me:  
🔗 [LinkedIn](https://www.linkedin.com/in/samrathareddy)

---

## 📊 Use Cases Simulated

- Analytics on user activity logs
- ETL from S3 → Redshift staging → analytics schema
- Reusable and modular SQL logic
- IAM role-based secure data access

---

## 📌 Future Improvements

- Integrate with Apache Airflow for orchestration
- Add test coverage and CI/CD pipeline
- Convert staging to Parquet-based optimized loading

---

⭐ **If you find this useful, give it a star and fork it!**
