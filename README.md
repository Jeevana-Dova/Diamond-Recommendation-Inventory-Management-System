# Diamond Recommendation & Inventory Management System

A full-featured diamond recommendation and inventory management application built with Python. This project includes personalized diamond filtering, GUI-based order placement, smart restocking logic, and secure admin price controls,all using real-world data.

## Project Overview

- **Timeline:** Nov 2024 – Jan 2025  
- **Goal:** Build a diamond recommendation and inventory system with real-time interaction and admin control  
- **Best Features:** Smart restocking, order tracking, and modular architecture  
- **Tech Stack:** Python, Pandas, Tkinter, CSV, Pytest

---

## System Features

### 1. Diamond Recommendation Engine
- GUI (Tkinter) for customer interaction
- Filter diamonds based on cut, carat, clarity, polish, and color
- Input validation with error handling

### 2. Order Management System
- Place orders with customer details and criteria
- Tracks sold stones to prevent double-selling
- Automatically saves to `order_details.csv` and `sold_stones.csv`

### 3. Admin Manager Console
- Login-protected access for managers
- Real-time price adjustment (±%) with reason logging
- Appends logs to `adjustment_log.txt`

### 4. Smart Restocking
- Analyzes sales trends vs. current stock
- Flags low-stock items dynamically
- Exports `inventory_status.csv` with visual indicators

### 5. Unit Testing Suite
- Pytest tests for recommendation, inventory control, validation logic
- Ensures robust, reliable behavior of each module

---

## Recommendation Workflow

- Users enter preferences (cut, carat, clarity)
- System validates input
- Matching diamonds are displayed from the dataset
- Admin can also view top-selling diamonds and adjust prices if needed

---
