
## 📘 2. Introduction

### 🎯 Purpose  
This project analyzes data from the used car market to uncover trends, customer preferences, and pricing influencers. The goal is to support strategic decisions around inventory, marketing, and sales optimization.

### 🧭 Objective of the Project  
The objective is to identify key factors that influence used car resale value. This includes analyzing brand preferences, fuel types, car condition, and pricing trends using Excel-based tools.

### ❓ Problem Being Addressed  
Used car dealers face challenges around inventory stocking, pricing accuracy, and predicting customer preferences. This analysis aims to answer:
- What features influence car resale value the most?
- Which attributes (brand, fuel type, color) attract customers?
- How can dealerships optimize stock and pricing based on data?

### 🛠️ Key Datasets and Methodologies  
- **Dataset**: Used cars dataset containing fields such as `make_year`, `mileage_kmpl`, `engine_cc`, `fuel_type`, `owner_count`, `price_usd`, etc.  
- **Tools**: Power BI (DAX Measures for deeper insight)

---

## 📖 3. Story of the Data

### 📂 Data Source  
The data was sourced from Kaggle.com.

### 📝 Data Collection Process  
Collected through sales logs, dealership records, and public datasets.

### 🧱 Data Structure  
Each row = one car  
Columns include car year, mileage, price, fuel type, insurance status, etc.

### ⭐ Important Features  
- `price_usd`: Target variable  
- `brand`, `fuel_type`, `color`: Indicators of buyer preference  
- `service_history`, `accidents_reported`, `insurance_valid`: Vehicle condition indicators

### ⚠️ Data Limitations or Biases  
- Incomplete service records  
- No location-based insights  

---

## 🔧 4. Data Splitting and Preprocessing

### 🧹 Data Cleaning  
- Removed duplicates  
- Fixed inconsistent labels (e.g., “gasoline” → “petrol”)

### 🔍 Handling Missing Values  
- No Missing Values 
- No deletion of rows to preserve data integrity

### 📊 Data Splitting  
- **Dependent Variable**: `price_usd`  
- **Independent Variables**: brand, fuel_type, mileage, engine size, etc.

### 🏢 Industry Context  
- **Automotive / Used Car Industry**  
- Data-driven pricing can boost profits and customer trust

### 👥 Stakeholders  
- Inventory Managers  
- Dealership Owners  
- Data Analysts  
- Sales Teams

### 🧩 Value to the Industry  
Insightful pricing and demand patterns support better sourcing, promotions, and ROI-focused operations.

---

## 🧪 5. Pre-Analysis

### 🔍 Key Trends  
- Nissan: most purchased brand  
- Petrol cars: most preferred  
- Black color cars sell fastest  
- Most cars are fully serviced  
- Cars with insurance are sold fastest

### 🔗 Potential Correlations  
- Full service + insurance = faster resale  
- Car age & price show inverse trend

### 💡 Initial Insights  
- Documentation improves car value perception  
- Visual traits like color play a big role

---

## 📊 6. In-Analysis

### 🧠 Unconfirmed Insights  
- Color preference might be cultural or psychological  
- Nissan’s sales dominance could relate to availability

### ✅ Recommendations  
- Increase stock of petrol-powered, black-colored Nissans  
- Ensure insurance and full service before listing  
- Offer bundled insurance or service promotions

---

## 📌 7. Post-Analysis & Insights

### 🏁 Key Findings  
- Revenue generated: **$71.80M**  
- Insured and serviced cars sell faster  
- Nissan and petrol models dominate

### 🔄 Comparison with Initial Findings  
- Hypotheses mostly confirmed  
- Surprising impact of car color

---

## 🧩 8. Recommendations & Observations

### 🎯 Actionable Insights  
1. Stock more Nissan, black, petrol-powered cars  
2. Emphasize cars with full documentation  
3. Offer post-sale insurance services

### ⚙️ Business Optimizations  
- Shift marketing to highlight "insured & serviced" benefits  
- Adjust sourcing to favor top-performing specs

### 🚨 Unexpected Outcomes  
- Color preference more impactful than expected  
- Fuel type mattered more than mileage

---

## ✅ 9. Conclusion

### 🎓 Key Learnings  
- Service history, insurance, and fuel type directly impact resale success  
- Psychological elements (e.g., color) influence decisions

### ⚠️ Limitations  
- No demographic or location data  
- Some missing values

### 🔮 Future Research  
- Incorporate customer segmentation (e.g., age, region)  
- Develop regression-based price prediction models

---

## 📚 10. References & Appendices

### 📌 References  
- Dataset: Kaggle  
- Tools: Power BI  
---
![TASK 34B](https://github.com/user-attachments/assets/81de9c46-0cbc-4d99-8fcc-849376fca8df)

