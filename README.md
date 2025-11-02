Medical Inventory Management System
📘 Overview

The Medical Inventory Management System is a Salesforce-based cloud application designed to automate and streamline the management of medical supplies, purchase orders, and supplier information. The system ensures that hospitals and healthcare organizations can efficiently manage stock levels, track supplier performance, and automate purchase workflows.

⚙️ Features

🔹 Product Management – Add, view, and update medical product details including stock levels and expiry dates.

🔹 Supplier Management – Maintain supplier details such as contact information and address.

🔹 Purchase Order Management – Automate the creation, tracking, and approval of purchase orders.

🔹 Inventory Transactions – Monitor incoming and outgoing stock through transaction records.

🔹 Automation with Flows & Triggers –

Flow: Automatically updates Actual Delivery Date.

Trigger: Calculates Total Order Cost dynamically.

🔹 Reports & Dashboards – Visualize purchase order summaries, supplier performance, and product stock levels.

🔹 Profiles & Roles – Role-based access control for Inventory and Purchase Managers.

🧩 Salesforce Objects Used
Object Name	Description
Product	Stores details of all medical products.
Supplier	Stores supplier contact and address details.
Purchase Order	Records orders placed to suppliers.
Order Item	Links products to purchase orders and manages quantity and cost.
Inventory Transaction	Tracks stock inflow and outflow.
🧠 Automation Logic

Flow: Updates Actual Delivery Date automatically (Order Date + 3 days).

Trigger: Calculates total amount for each Purchase Order based on Order Items.

🧱 Roles and Permissions
Role	Description
Inventory Manager	Manages stock and product updates.
Purchase Manager	Handles supplier orders and approvals.
System Administrator	Has full control over all modules and automations.
📊 Dashboards & Reports

Reports:

Purchase Orders Based on Suppliers

Complete Purchase Details Report

Dashboard:

Medical Inventory Dashboard displaying order summaries, total costs, and supplier performance metrics.

🏗️ Technology Stack
Component	Technology Used
Platform	Salesforce Cloud (SaaS)
Logic	Apex Trigger, Flow
UI	Salesforce Lightning App
Database	Salesforce Object Database
Reports	Salesforce Report Builder & Dashboard
Security	Profiles, Roles, Permission Sets
📋 Project Setup Instructions

Sign up for a Salesforce Developer Account → developer.salesforce.com/signup

Log in to Salesforce and open Setup.

Create Custom Objects for Product, Supplier, Purchase Order, Order Item, and Inventory Transaction.

Add Tabs for each object and configure Page Layouts.

Create Flows, Apex Triggers, and Reports as described in the project guide.

Build the Lightning App named Medical Inventory Management.

Create Profiles, Roles, and Permission Sets for access control.

Deploy and test the complete functionality.

📈 Example Use Case

A purchase manager creates a new purchase order for a supplier.

The system automatically calculates the total order cost using triggers.

Once the order is confirmed, the inventory is updated via flows.

The dashboard reflects the updated order summary and supplier performance.

📚 References

Salesforce Developer Documentation

Trailhead Salesforce Learning Modules
