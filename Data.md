# Data Quality

## Overview

Data quality refers to the condition of data based on how well it satisfies business requirements. High-quality data is accurate, complete, consistent, timely, valid, and unique, enabling organizations to make reliable decisions and improve operational efficiency.

---

## Why Data Quality Matters

Poor data quality can lead to:

* Incorrect business decisions
* Revenue loss
* Customer dissatisfaction
* Compliance risks
* Inefficient business processes

Good data quality ensures that data is trustworthy and fit for its intended purpose.

---

# The Six Dimensions of Data Quality

## 1. Accuracy

### Definition

Data should correctly represent real-world entities and events.

### Example

| Customer ID | Name       | Email                                   |
| ----------- | ---------- | --------------------------------------- |
| 101         | John Smith | [john@gmail.com](mailto:john@gmail.com) |

Incorrect:

| Customer ID | Name       | Email                                   |
| ----------- | ---------- | --------------------------------------- |
| 101         | John Smith | [john@gmial.com](mailto:john@gmial.com) |

---

## 2. Completeness

### Definition

All required records and attributes should be available.

Example:

| Customer | Phone     |
| -------- | --------- |
| John     | 987654321 |
| Alice    | NULL      |

Missing phone number indicates incomplete data.

---

## 3. Consistency

### Definition

The same information should remain identical across systems.

Example

CRM:

```text
Country = Germany
```

ERP:

```text
Country = Deutschland
```

These represent the same country but are inconsistent.

---

## 4. Timeliness

### Definition

Data should be current and available when required.

Example

Inventory updated:

```text
Last Updated:
January 2026
```

Current date:

```text
June 2026
```

The inventory data may no longer be reliable.

---

## 5. Validity

### Definition

Data should follow predefined rules and formats.

Valid email:

```text
john@gmail.com
```

Invalid email:

```text
johngmail.com
```

---

## 6. Uniqueness

### Definition

Duplicate records should not exist.

Example

| Customer ID | Name |
| ----------- | ---- |
| 101         | John |
| 101         | John |

Duplicate customer records reduce data quality.

---

# Summary

| Dimension    | Goal                   |
| ------------ | ---------------------- |
| Accuracy     | Correct information    |
| Completeness | No missing data        |
| Consistency  | Same values everywhere |
| Timeliness   | Up-to-date information |
| Validity     | Follows business rules |
| Uniqueness   | No duplicates          |

---

# Real-World Applications

* Customer Master Data
* Healthcare Records
* Banking Transactions
* Supply Chain Management
* Renewable Energy Asset Management
* Data Warehouses

---

# Common Interview Questions

### What are the six dimensions of data quality?

Accuracy, Completeness, Consistency, Timeliness, Validity, and Uniqueness.

---

### How do you improve data quality?

* Data validation
* Data cleansing
* Deduplication
* Standardization
* Automated quality checks
* Monitoring dashboards

---

### Tools Used

* SQL
* Python (Pandas)
* Excel
* Power BI
* Great Expectations
* dbt Tests

---

# Key Takeaways

* Data quality is essential for trustworthy analytics.
* The six dimensions help measure whether data is fit for use.
* Continuous monitoring and validation are critical to maintaining high-quality datasets.

