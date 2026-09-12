# Hi, I'm Aditya 👋
**4th Year B.Tech Computer Science Student | Learning Data Engineering**

I build modular, containerized data pipelines and analytical data warehouses. I focus on core Data Engineering concepts: ETL orchestration, Medallion Architecture (Bronze/Silver/Gold), dimensional modeling, and Spark data processing.

---

### 🛠️ Tech Stack & Skills

* **Languages:** Python, SQL
* **Data Processing & Orchestration:** PySpark, Apache Airflow, Pandas
* **Data Warehousing & Storage:** MySQL (Star Schema Modeling)
* **Infrastructure & Tools:** Docker, Docker Compose, VS Code
* **Visualization & UI:** Tableau Public, Streamlit

---

### 🚀 Featured Project

#### 📦 E-Commerce Data Engineering Pipeline & BI Dashboard
An end-to-end, containerized batch processing pipeline built with **PySpark**, **Apache Airflow**, and **Docker** to transform ~100k raw e-commerce records into an optimized Star Schema Data Warehouse.

* **Architecture:** Medallion Design (Bronze $\rightarrow$ Silver $\rightarrow$ Gold)
  * **Bronze (Ingestion):** Ingested raw multi-table CSVs enforcing schema-on-read via PySpark.
  * **Silver (Cleansing):** Automated null filtering, deduplication, order status filtering, and timestamp casting.
  * **Gold (Warehouse):** Modeled data into a Star Schema (`fact_sales` + 4 dimension tables) and loaded into MySQL via JDBC.
* **Orchestration:** Directed Acyclic Graphs (DAGs) in Apache Airflow managing task dependencies, retries, and execution flow.
* **Monitoring & BI:** Built a custom Streamlit UI for system status/job control and a Tableau Public dashboard tracking $16.57M+ in processed metrics.

---

### 📊 Key Data Engineering Concepts Applied
* **Dimensional Modeling:** Designing Star Schemas (`fact_sales`, `dim_customers`, `dim_products`, `dim_sellers`, `dim_time`).
* **Data Hygiene:** Handling schema preservation, currency standardization, and filtering canceled/corrupted records.
* **Containerization:** Running pipeline components across isolated Docker containers.

---

### 📫 Connect With Me
* **LinkedIn:** [adityamishra-dataeng](https://www.linkedin.com/in/adityamishra-dataeng/)
