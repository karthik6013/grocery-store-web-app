# grocery-store-web-app
# Grocery Store Management System - Python Project  

This project involves building a **Grocery Store Management Application** using a **three-tier architecture**:  

1. **Frontend:** HTML, CSS, JavaScript, and Bootstrap  
2. **Backend:** Python with Flask  
3. **Database:** MySQL  

![Homepage](homepage.JPG)  

## Installation Instructions  

To set up MySQL on Windows, download it from: [MySQL Installer](https://dev.mysql.com/downloads/installer/)  

Install the required Python package:  
```bash
pip install mysql-connector-python
```

## Feature Enhancements & Bug Fixes  

After launching the application, user feedback highlighted several areas for improvement. Here are the enhancements and fixes to be implemented:  

### **Products Module**  
1. **Edit Product Feature:** Add an "Edit" button next to the "Delete" button in the product list, allowing users to modify existing product details.  
2. **UOM (Unit of Measurement) Management:** Introduce a form for adding new UOMs (e.g., "Cubic Meter" for selling wood). This requires modifications in both the frontend UI and the backend server.  

### **Orders Module**  
3. **Validation Enhancements:** Implement validation checks for customer names, item names, and quantities to prevent empty or incorrect order entries. This update is specific to the frontend UI.  
4. **Grand Total Calculation Fix:** Resolve a bug where manually altering the total price of an item does not update the grand total of the order.  
5. **Order Details View:** Add a "View" button in the order list grid. Clicking it should display a detailed breakdown of the selected order, including item names, quantities, and individual prices.  

By implementing these improvements, the application will become more user-friendly and robust. 🚀
