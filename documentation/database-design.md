# AgriFusion – Database Design Documentation

## 1. Project Overview

AgriFusion is a relational database project designed to manage agricultural operations. It organises information about farms, crops, production, IoT monitoring, inventory, suppliers, and sales.

## 2. Technologies Used

- MySQL
- SQL
- Relational Database Design

## 3. Database Structure

The database contains 26 tables organised into five main areas:

### Farm Management
- Farm
- Field
- FarmPhone
- FarmEmail

### Crop and Production
- Crop
- Planting
- Harvest
- Task

### IoT and Sensor Monitoring
- Gateway
- Device
- Sensor
- Calibration
- Reading
- Alert

### Inventory and Supplier Management
- Supplier
- Fertilizer
- Pesticide
- PurchaseOrder
- Inventory
- UsageLog

### Sales and Distribution
- Buyer
- QualityGrade
- Contract
- Shipment
- Invoice
- Payment

## 4. Database Relationships

The database uses Primary Keys (PK) to uniquely identify records and Foreign Keys (FK) to establish relationships between related tables.

These relationships help maintain data consistency and organise agricultural information efficiently.

## 5. Entity Relationship Diagram

The AgriFusion ER diagram illustrates the database entities, their attributes, and the relationships between them.

## 6. How to Run

1. Open MySQL Workbench or another compatible MySQL environment.
2. Open the `agriFusion.sql` file.
3. Execute the SQL script.
4. The database and its tables will be created.
