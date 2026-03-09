# Logistics Charge Analysis System

This project analyzes courier shipping charges for an e-commerce company (ShopX) to verify whether delivery partners are charging the correct shipping cost for each order.

---

# Business Problem

ShopX ships thousands of orders every day through courier partners.

Courier companies charge shipping fees based on:

• Shipment weight  
• Delivery distance / zone

ShopX noticed that courier charges are extremely high and wants to verify whether courier companies are billing correctly for each order.

---

# Objective

The objective of this project is to:

• Calculate shipment weight using product data  
• Determine correct weight slabs  
• Identify delivery zones  
• Calculate expected shipping charges  
• Compare expected charges with courier invoice charges  
• Detect overcharged and undercharged shipments

---

# Methodology

Step 1  
Calculate total shipment weight using product weight data.

Step 2  
Convert total weight into courier weight slabs (0.5 kg increments).

Step 3  
Identify delivery zone using warehouse and customer pincode mapping.

Step 4  
Calculate expected courier charges using the courier rate card.

Step 5  
Compare expected charges with actual invoice charges.

Step 6  
Identify whether the shipment was:

• Correctly charged  
• Overcharged  
• Undercharged

---

# Output Files

## Order Level Calculation

Detailed order-level analysis including:

• Order ID  
• AWB Number  
• Total weight calculated by ShopX  
• Weight slab  
• Courier charged weight  
• Delivery zone comparison  
• Expected charge  
• Billed charge  
• Difference in charges

---

## Summary Table

Overall results including:

• Total orders correctly charged  
• Total orders overcharged  
• Total orders undercharged

---

# Tools Used

Python  
Pandas  
Excel  
Data Analysis  

---

# Dataset

The raw dataset used in this project is not included in this repository due to privacy considerations.

---

# Author

Prachi Upadhayay
