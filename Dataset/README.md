
# 📂 Ice Cream Sales Analysis – Dataset Documentation

## 📌 Overview

This folder contains the datasets used for the Ice Cream Sales Analysis Power BI project.

The datasets include transactional sales information from 2014, 2015, and 2016, along with supporting information about products, categories, subcategories, geographical locations, and sales representatives.

The data is organised into multiple CSV and Excel files to support data modelling and business analysis in Power BI.

## 📁 Dataset Files

| File Name | Description |
|---|---|
| sales 2014.csv | Sales transactions for 2014 |
| sales 2015.csv | Sales transactions for 2015 |
| sales 2016.csv | Sales transactions for 2016 |
| Product.csv | Product details, pricing, and standard costs |
| Categories.xlsx | Product category information |
| SubCategories.xlsx | Product subcategory information |
| Geography.xlsx | Country and geographical reference information |
| SalesRep.xlsx | Sales representative details |

## 📊 Dataset Statistics

### Sales Datasets

| Dataset | Number of Records |
|---|---:|
| Sales 2014 | 12,248 |
| Sales 2015 | 12,500 |
| Sales 2016 | 12,194 |
| **Total** | **36,942** |

The combined sales datasets contain 36,942 transaction records.

### Supporting Datasets

| Dataset | Description |
|---|---|
| Product | 13 data rows, representing 11 unique Product IDs |
| Categories | 2 product categories |
| SubCategories | 4 product subcategories |
| Geography | 3 countries |
| SalesRep | 7 sales representatives |

## 🧾 Sales Dataset – Column Description

The three yearly sales files contain the following columns:

| Column | Description |
|---|---|
| fSalesPrimaryKey | Unique transaction identifier |
| ProductID | Identifier for the product sold |
| SalesRepID | Identifier for the sales representative |
| Location | Country and city of the transaction |
| Date | Transaction date |
| Units | Number of units sold |
| PercentOfStandardCost | Percentage factor associated with standard cost |
| RevenueDiscount | Discount factor applied to revenue |

## 🍦 Product Dataset – Column Description

| Column | Description |
|---|---|
| ProductID | Unique product identifier |
| Sub Category Key | Identifier linking the product to its subcategory |
| Color | Product colour |
| ProductName | Name of the ice cream product |
| RetailPrice | Retail selling price |
| StandardCost | Standard cost of the product |

## 🗂️ Categories Dataset

Contains information about the main product categories.

- Special
- General

Columns:
- CategoryKey
- Category

## 🗂️ SubCategories Dataset

Contains subcategory information linked to the main categories.

| SubCategoryKey | SubCategory Name |
|---|---|
| 1 | Extra |
| 2 | Regular |
| 3 | Micro |
| 4 | Super |

Additional column:
- CategoryKey

## 🌍 Geography Dataset

Contains geographical reference information for the sales analysis.

Countries covered:
- India
- Germany
- United States

Cities represented in the sales data:
- Bangalore
- Chennai
- Mumbai
- Berlin
- Dresden
- Hamburg
- New York

## 👥 Sales Representative Dataset

Contains sales representative identifiers and their corresponding names.

Columns:
- SalesRepID
- Sales Rep Name

There are seven sales representatives included in the dataset.

## 🔄 Data Preparation & Modelling

The following preparation activities are relevant to integrating the datasets:

1. Combined the three yearly sales datasets for consolidated analysis.
2. Reviewed column names and data types.
3. Checked product and sales representative identifiers.
4. Connected sales records with product information.
5. Established category and subcategory relationships.
6. Connected geographical information for country and city analysis.
7. Prepared date information for year, month, and daily analysis.

## 🛠️ Tools Used

- Microsoft Excel
- Microsoft Power BI
- Power Query
- DAX

**Author:** Srinidhi Bhat
