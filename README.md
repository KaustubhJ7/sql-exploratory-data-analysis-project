# SQL Exploratory Data Analysis (EDA) Project

Leveraged advanced SQL techniques (CTEs, Window Functions) to perform exploratory data analysis and identifying key trends

## 📌 Project Overview
This repository contains an end-to-end Exploratory Data Analysis (EDA) project executed entirely in SQL. The objective is to dive deep into a raw business dataset analyzing areas such as retail sales, customer behavior, or user engagement to extract actionable trends, identify operational anomalies, and deliver data-driven insights.

By querying structural patterns and trends directly from the database, this project aims to bridge the gap between messy, unstructured relational tables and strategic business decisions.

## 🚀 Key Business Questions Answered
* **[Question 1]:** What are the top-performing products driving the most revenue?
* **[Question 2]:** How do customer purchasing frequencies change month-over-month (MoM)?
* **[Question 3]:** Where are the critical data inconsistencies or anomalies (such as duplicate entries or unexpected gaps)?

## 🛠️ Tech Stack & Database Environment
* **SQL Dialect:** SQL Server
* **Dataset:** Rather than using a pre-existing public dataset, I synthesized a custom relational dataset designed to simulate a **retail e-commerce platform**.
* **Tools Configuration:** Database server hosting and query building via SQL Server Management Studio (SSMS).

## 🧠 Advanced SQL Techniques Implemented
To avoid simple aggregations and delve into sophisticated data modeling, this project heavily implements:
* **Common Table Expressions (CTEs):** Used to modularize highly complex queries, creating temporary result sets for multi-layered business logic.
* **Window Functions (`RANK`, `DENSE_RANK`, `LAG`, `LEAD`):** Applied to isolate rolling performance metrics, pinpoint month-over-month changes, and handle sophisticated time-series analysis.
* **Conditional Logic (`CASE WHEN`):** Utilized for dynamic user segmentation and behavioral buckets.
* **Advanced Joins & Aggregate Functions:** Leveraged to combine normalized schema architectures and calculate deep statistical markers.
