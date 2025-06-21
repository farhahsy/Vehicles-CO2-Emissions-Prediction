# 📊 Dashboard: Vehicle CO₂ Emissions Insights

This dashboard was developed using **Power BI** to present key insights derived from vehicle CO₂ emissions data (2015–2024). It provides an interactive visual summary of the analysis and predictive modeling process carried out in this project.

---

## 🔍 Key Dashboard Components

### 1. **Vehicle Class vs Average CO₂ Emissions**
- Van: Passenger vehicles show the highest average CO₂ emissions (~389 g/km).
- Compact and subcompact vehicles are among the most fuel-efficient.
- Useful for identifying emission-heavy vehicle types.

---

### 2. **Fuel Consumption vs CO₂ Emissions**
- Shows a clear positive correlation between combined fuel consumption and CO₂ output.
- Vehicles with high fuel consumption tend to emit more CO₂.

---

### 3. **Engine Size vs Average CO₂ Emissions**
- Engine sizes from 0.9L to 2.4L show a gradual increase in average emissions.
- Vehicles with engines above 2.0L show emissions over 200 g/km consistently.

---

### 4. **Total CO₂ Emissions by Model Year**
- Emissions vary year-to-year, peaking in certain years such as 2016 and 2024.
- Trends suggest increasing emissions in recent years despite sustainability efforts.

---

### 5. **Average CO₂ Emissions by Fuel Type**
- Ethanol (E84) and Premium Gasoline emit the most CO₂.
- Natural Gas vehicles (NGV) show the lowest average emissions (~213 g/km).

| Code | Fuel Type        | Avg CO₂ Emissions (g/km) |
|------|------------------|---------------------------|
| E    | Ethanol (E84)    | 273.60                    |
| Z    | Premium Gasoline | 270.63                    |
| D    | Diesel           | 251.23                    |
| X    | Regular Gasoline | 235.25                    |
| N    | Natural Gas      | 213.00                    |

---

### 6. **Cylinders vs CO₂ Emissions**
- More cylinders generally result in higher emissions.
- Vehicles with 10 cylinders emit over 560 g/km on average.

---

### 7. **Transmission Type Comparison**
- Manual transmission vehicles tend to emit less CO₂ (avg ~233 g/km) compared to automatic ones (avg ~256 g/km).

---

### 8. **Predicted vs Actual CO₂ Emissions**
- Scatter plot validates the accuracy of the ML model.
- Predicted values follow a close linear trend to actual CO₂ outputs, indicating a good model fit.

---

### 9. **Average Predicted CO₂ Emissions by Vehicle Class and Brand**
- Breakdown by brands like Honda, Mazda, Kia, and Lexus.
- Helps visualize which brand and class combinations are more environmentally friendly.

---

## 📂 How to Use the Dashboard

[![Dashboard Demo Video](./dashboard/screenshots/video_thumbnail.png)](https://drive.google.com/file/d/1HM4pB_vNAFKSUTVr5-X3Oo2h0NpZRx3r/view?usp=sharing)

---

## 📸 Screenshots

![CO2 Emissions by Vehicle Class](./dashboard/screenshots/vehicle_class_emissions.jpg)

![CO2 Emissions by Vehicle Class (1)](./dashboard/screenshots/vehicle_class_emissions_1.jpg)

![CO2 Emissions by Vehicle Class (2)](./dashboard/screenshots/vehicle_class_emissions_2.jpg)

