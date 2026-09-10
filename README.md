# 🎯 Power BI 10-Day Learning Challenge

**Status:** 📚 Actively Learning | 💼 Open to Entry-Level Opportunities

Entry-level Power BI analyst building a professional portfolio through structured daily projects.

---

## 🚀 About This Challenge

I'm learning to think like a data professional by building production-quality analytics projects. This repository documents every step of my journey — not just the finished dashboards, but the actual thinking behind them.

**Why?** Because real analysts spend 80% of their time on data cleaning and transformation, and 20% on visualizations. This portfolio shows the actual work.

---

## 📊 Project 1: Retail Analytics Dashboard

### Day 1 ✅ - Data Foundation & Star Schema
**Objective:** Build a clean, queryable data foundation

**What I Did:**
- Loaded 3 CSV files (Orders, Products, Customers) into Power BI
- Fixed data quality issues:
  - Promoted headers (first row wasn't being recognized)
  - Corrected data types (dates, numbers, text)
  - Verified column names and structure
- Built a **star schema** with proper relationships:
  - **Fact Table:** retail_orders (800 rows)
  - **Dimension Tables:** retail_customers, retail_products
  - **Relationships:** One-to-Many (customers → orders, products → orders)

**Key Learning:**
> "Clean data with proper relationships is worth 10 pretty dashboards with messy data."

**Result:** A queryable data model ready for analysis

---

### Day 2 ✅ - Power Query Deep Dive
**Objective:** Transform raw data into business insights using 4 core Power Query techniques

**What I Did:**

**1. Group By - Customer Summary**
- Aggregated 800 orders into 60 unique customers
- Created metrics:
  - Total Sales (per customer)
  - Total Orders (count)
  - Total Profit (per customer)

**2. Conditional Column - Customer Value Classification**
- Created business logic:
  - VIP: Sales > $10,000
  - High Value: Sales $5,000–$10,000
  - Regular: Sales < $5,000
- Now can segment customers by value instantly

**3. Group By - Regional Summary**
- Aggregated same metrics by geographic region
- Created separate summary for regional analysis

**4. Merge - Add Customer Demographics**
- Joined customer summary with customer table
- Added: Customer Name, Segment, Region
- Used Left Outer Join to preserve all customers

**5. Append - Unify Summaries**
- Combined customer-level and regional summaries
- Created single unified analytics table

**Key Learning:**
> "Merge and Append let you combine different levels of analysis into one queryable table. This is how analysts build flexible data structures."

**Result:** 4 professional Power Query transformations in one project

---

## 🛠️ Skills Demonstrated

### Power Query (Data Transformation)
- ✅ Loading multiple file types
- ✅ Data type detection & correction
- ✅ Group By (aggregation at different levels)
- ✅ Conditional Column (IF logic)
- ✅ Merge (SQL JOIN equivalent)
- ✅ Append (SQL UNION equivalent)
- ✅ Professional step naming (documentation)

### Data Modeling
- ✅ Star schema design
- ✅ Relationship creation (1-to-Many)
- ✅ Fact vs Dimension tables
- ✅ Cardinality understanding

### Professional Practices
- ✅ Descriptive naming conventions
- ✅ Commented transformation steps
- ✅ Data quality validation
- ✅ Documentation of logic

---

## 📁 Project Structure
