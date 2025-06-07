# Paint-damage-analysis-of-logistics-
# 🚚 Logistics Paint Damage Analysis – India’s Largest Paint Company

This project investigates the causes of paint tin damage during shipment from various warehouses to dealers across India. The objective is to identify a few key factors (based on the 80:20 principle) that contribute to the majority of the damage and financial losses.

## 📊 Problem Statement

Paint tins damaged during shipping are returned by dealers, leading to loss of revenue. The cause could be:
- Specific dealers
- Particular warehouses
- Tin sizes or paint types
- The type of transport vehicle
- Or combinations thereof

The aim is to **analyze the shipment data** and pinpoint high-impact areas to reduce overall damage and loss.

## 🛠 Tools & Technologies
- **Python**
- **Pandas** for data manipulation
- **Seaborn** and **Matplotlib** for visualization
- **EDA (Exploratory Data Analysis)** and domain-driven rule modeling

## 📁 Dataset Overview

| Column         | Description |
|----------------|-------------|
| Date           | Shipment date |
| Dealer         | Dealer code |
| City           | Warehouse location |
| Product        | 9-digit product code (Type + Color + Tin Size) |
| Vehicle        | Type of vehicle (Minitruck, Vikram, AutoRick) |
| Shipped        | Number of tins shipped |
| Returned       | Number of tins returned |

## 🔍 Key Insights

- **Overloading is a major cause** of damage. Vehicles carrying more than safe limits see higher damage rates.
- **Larger tin sizes (e.g., 987, 890)** are more prone to damage.
- Certain **warehouses and dealers** show consistently higher return rates.
- **Expensive paint types** result in higher financial losses when damaged.
- **Vehicle type matters:** Autorickshaws and Vikrams tend to have higher damage rates than Minitrucks.

## 📈 Visual Highlights

Visualizations included:
- Damage & loss by city, vehicle, dealer, tin size, paint type
- Heatmaps: Financial loss and damage rate breakdowns
- Monthly trends in damage rate
- Overloading impact analytics




### 👨‍💻 Author

**Bhawana Rakshit**  
Python | Data Analysis | Logistics Optimization  

---

### 📜 License

This project is open-source under the [MIT License](LICENSE).

