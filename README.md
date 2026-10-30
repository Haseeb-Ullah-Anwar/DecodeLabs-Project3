# 💾 Project 3: Relational SQL Database Architecture & Engineering
**DecodeLabs Data Analytics Internship | Production Database Scripting Track**

## 🏷️ Project Title
**Enterprise E-Commerce Transactional Ledger Ingestion & Relational Analytics Scripting**

## 📝 Detailed Project Overview
This phase translates our fully-sanitized spreadsheet database into Microsoft SQL Server Management Studio (SSMS) to execute deep data retrieval, criteria-based aggregation, and promotional yield analysis. The relational database pipeline is explicitly configured to ingest exactly **1,200 transactional records** and process analytical metrics mapping safely to relational database engine constraints.

---

### ⚙️ Core Database Engine Computational Constraints

Every analytical extraction scripted within this pipeline respects the hardcoded mathematical processing order of relational database query optimizers:
👉 `FROM ➡️ WHERE ➡️ GROUP BY ➡️ HAVING ➡️ SELECT ➡️ ORDER BY`

---

### 🛠️ Technical Query Implementations & Structural Logic

#### Task 01 | Multi-Criteria Transactional Filtering
* **Objective:** Isolate high-priority running orders based on explicit operational states.
* **SQL Logic:** Applied precise boolean conjunctions (`WHERE OrderStatus = 'Shipped' AND PaymentMethod = 'Credit Card'`) to screen active financial loops and remove pending or cancelled traffic distortions.

#### Task 02 | Categorical Aggregations & Volume Compression
* **Objective:** Compress 1,200 raw data rows into clean category-level financial metrics.
* **SQL Logic:** Deployed `GROUP BY Product` alongside mathematical functions (`COUNT(OrderID)`, `SUM(Quantity)`, and `ROUND(SUM(TotalPrice), 2)`). This ensures exact metric rounding to avoid float data errors.

#### Task 03 | Tukey's IQR Validation Ingestion
* **Objective:** Inject Project 2's statistical upper-bound limit into the active SQL query stream.
* **SQL Logic:** Hardcoded the numerical threshold baseline (`WHERE TotalPrice > 3330.41`) inside the row-filtering pipeline to isolate exactly the **8 absolute VIP corporate transactions** pulling macro revenue parameters.

#### Task 04 | Marketing Promotional Yield Analysis (`HAVING` Controls)
* **Objective:** Filter grouped marketing coupon yields to identify high-yield promotional strategies.
* **SQL Logic:** Combined string exclusions (`CouponCode IS NOT NULL AND CouponCode <> 'NO_COUPON'`) with a trailing evaluation barrier (`HAVING SUM(TotalPrice) > 20000.00`). Sorted results using `ORDER BY Campaign_Gross_Yield DESC` to isolate top performers like `FREESHIP` and `SAVE10`.

#### Task 05 | Traffic Channel Acquisition Matrix
* **Objective:** Rank client acquisition channels based on their direct gross revenue contribution.
* **SQL Logic:** Structured aggregation blocks on `ReferralSource` variables, removing empty anomalies (`WHERE ReferralSource IS NOT NULL AND ReferralSource <> ''`) to rank channel values from highest to lowest velocity.

---

### 🖼️ SSMS Production Grid Proofs

#### 1. Outlier Validation (Task 03 - 8 VIP Rows Captured):
![SSMS Outlier Results](Task%203%20-%20Outlier%20Forensic%20Audit.png)

#### 2. Referral Traffic Acquisitions (Task 05 Grid Output):
![SSMS Channel Results](Task%205%20-%20Referral%20Source%20Performance.png)

---

## ⚙️ How to Run & Execute This Project
1. Ingest the raw data schema into your local Microsoft SQL Server instance (`SSMS`).
2. Run the master script file: **`Decode Labs(Ecomerce Data).sql`** inside the database workspace.
3. Execute queries sequentially to review output grids mapping to our 5 core operational targets.
