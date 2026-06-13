# Data_analysis----Customer_360_project
## 📝 Project Description
This analytics solution creates a unified **Customer 360 Profile (Single Customer View)** from decentralized relational e-commerce tables. Using **Python**, the pipeline integrates disparate transactional ledgers, geolocation indices, shipping logs, payment options, and consumer feedback reviews to engineer high-signal behavioral markers.

The final consolidated model calculates total customer spend values, average basket sizes, profit margins, categorical reliance flags, installment behaviors, and churn patterns. The engineered features isolate elite customer segments and predict retention liabilities.

---

## 📊 Production Data Asset Output
> [!IMPORTANT]
> IMPORTANT :- RAW DATA(Customer_360_project) AND OBTAINED\FILTER DATA ARE IN SEPARATE ZIP FILES(Customer_360_project_answers). DOWNLOAD IT TO VIEW COMPLETE FILE.

---

## 📐 Data Integration & Feature Engineering Architecture

The execution steps compile raw transactional files down to unified customer behavioral states:

| Source File Component | Field Dimensions Extracted | Engineered Behavioral Feature Target |
| :--- | :--- | :--- |
| 🏷️ **CUSTOMERS.csv** | `customer_id`, `zip_code`, `state` | Core Demographic Mapping Index |
| 📦 **ORDERS.csv** | Timestamp records, Delivery log statuses | Recency Metrics & Churn Status flags |
| 💸 **ORDER_ITEMS.csv** | Price rates, Freight values, Seller keys | `total_act_amount`, `avg_basket_value` |
| 💳 **ORDER_PAYMENTS.csv** | Payment forms, Installment frequencies | `decile_payment_installments` scoring |
| ⭐ **ORDER_REVIEW_RATINGS.csv**| Numeric scores ($1 \rightarrow 5$) | `review_flag` tracking customer satisfaction |
| 🗃️ **PRODUCTS.csv** | Category tags (`Bed_Bath_Table`, `Toys`) | Categorical split margins (`cat_pur_...`) |

---

## 🔍 Core Engineered Consumer Features

* **💰 Value

  
