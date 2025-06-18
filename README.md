# 🚗 Supply Chain Management System – Accelero Motors

A DBMS project designed to streamline the **Supply Chain Management** operations of a fictional automotive company, **Accelero Motors**, from production to final customer sales.

> 📁 Built as part of the IT-214 DBMS course under the guidance of Prof. P.M. Jat.

---

## 🧠 Objective

To design and implement a relational database that efficiently handles:

- Supplier relationships  
- Manufacturing logistics  
- Inventory and assembly tracking  
- Dealer management  
- Customer sales and transactions  

---

## 🏢 Application Users

- **Accelero Motors (Manufacturer)**: Core user managing suppliers, production, assembly, and dealers.  
- **Suppliers**: Categorized into raw materials, components, and sub-assembled parts suppliers.  
- **Dealers**: Purchase from manufacturers and sell to customers.  

---

## 🔄 How the Supply Chain is Formed

The entire supply chain is divided into three major stages: **Suppliers → Manufacturers → Dealers**. Here's a visual breakdown:

![Supply Chain Diagram](https://raw.githubusercontent.com/ayushijani/Supply-Chain-Management/main/Assets/Screenshot%202025-06-18%20121523.png)

1. **Suppliers** are classified into three types:
   - **Raw-material Suppliers**: Provide materials like steel, rubber, plastic, etc.
   - **Component Suppliers**: Deliver parts like brakes, seats, batteries, etc.
   - **Sub-assembled Parts Suppliers**: Supply partially built modules like engines or gearboxes.

2. **Manufacturers (Accelero Motors)** receive parts from all supplier types and:
   - Assemble and produce key parts
   - Integrate all modules in assembly plants
   - Perform testing and quality assurance

3. **Dealers** procure the final tested cars from the manufacturer and:
   - Add cars to their stock
   - Sell to customers
   - Maintain sales records and customer data

This structure ensures end-to-end traceability, optimized logistics, and accurate data tracking at every level.

---

## 🛠️ Key Features

### ➤ Suppliers
- Register and categorize suppliers  
- Track self-produced vs. outsourced parts  
- Manage supply and transaction records  

### ➤ Manufacturers
- Record in-house production  
- Handle assembly and quality checks  
- Manage production schedules and shipments  

### ➤ Dealers
- Register dealerships  
- Place orders and manage car stock  
- Track customer transactions  

---

## 🔍 Sample Queries

- Top-selling car models of the year  
- Suppliers dealing with both in-house and outsourced parts  
- Total production cost of a car model  
- Dealer with the highest car sales  
- Year-wise revenue reports  

---

## 👩‍💻 Team T212

- Ayushi Jani – 202201141 *(Group Representative)*  
- Kashvi Bhanderi – 202201149  
- Pari Chauhan – 202201189  
- Bansi Patel – 202201190  

---

> 🧾 **Note**: This project was developed purely for academic purposes and simulates a complete SCM system from a database design perspective.

