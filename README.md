# Sales_fusion-live-inventory-dashboard-

This project is a complete solution to track the stock in the shops, identify expired stocks, and automate mails to refill the stock using **SharePoint**, **Excel**, **Power Automate**, and **Outlook**.

## 📌 Project Objective

To create a centralized system that:
- Tracks stock in the shops
- Highlights the highly marketed produck among all for every day
- Sends automated notifications to compamiies and coustomers
- Provides dashboards for quick decision-making

---

## 🧱 Components Used

### 🔷 SharePoint List
A custom SharePoint list to store:
- UNIQUE_ID_OF_PRODUCT
- CATEGORY_OF_PRODUCT
- PRODUCT_NAME
- NO_OF_STOCK_UNIT_PURCHASED_BY_STORE
- NO_OF_STOCK_LEFT
- UNIT_COST_FROM_COMPANY_TO_STORE
- MRP
- DISCOUNT_GIVEN_BY_COMPANY_TO_STORE
- ACTUAL_PRICE_TO_CUSTOMER
- EXPIRY_DATE_OF_PRODUCT
- DATE_OF_STOCK_PURCHASED
- PURCHASED_COMPANY_NAME
- COMPANY_EMAIL_FOR_ORDERING
- DISCOUNT
- PRICE_AFTER_DISCOUNT
- SOLD_STOCK
- PROFIT
- DAYS LEFT
- EXPIRY STATUS


### 📊 Excel Dashboard
Features:
- Pivot Tables for stock distribution & easy understanding.
- Conditional formatting to highlight discount ststus.
- Charts for visualization
- Slicers for filtering by categories, items, etc.

### 🔁 Power Automate Flows
1. **Coustomers bill Flow**  
   Sends an email to the coustomer when they buyed the stock in the shop of the items thet buyed.

2. **Stock Reminder Flow**  
   Notifies the companies if the stock is below 10% to the amount they send before.

### ✉️ Outlook
- Automated email notifications using dynamic content.

---

## 🙋‍♂️ Created by

**Alla Lohith Lakshmi Reddy**  
Drive Ready Trainee @ Technical Hub  
Aditya College of Engineering and Technology

---
