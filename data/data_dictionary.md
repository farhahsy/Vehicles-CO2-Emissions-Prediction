# 📘 Data Dictionary

This document describes the key variables used in the dataset for the project.

---

## 🚗 Model

| Code      | Description                                                                 |
|-----------|-----------------------------------------------------------------------------|
| AWD       | All-Wheel Drive — vehicle designed to operate with all wheels powered      |
| 4WD / 4X4 | Four-Wheel Drive — can operate with either two or four wheels powered      |
| FFV       | Flexible-Fuel Vehicle — operates on gasoline and ethanol blends (up to E85)|
| CNG       | Compressed Natural Gas                                                     |
| NGV       | Natural Gas Vehicle                                                        |
| SWB       | Short Wheelbase                                                            |
| LWB       | Long Wheelbase                                                             |
| EWB       | Extended Wheelbase                                                         |

---

## 🚘 Class

Vehicle body and size classification:

- Two-seater  
- Minicompact  
- Subcompact  
- Compact  
- Mid-size  
- Full-size  
- Station wagon: Small  
- Station wagon: Mid-size  
- Pickup truck: Small  
- Pickup truck: Standard  
- Sport utility vehicle: Small  
- Sport utility vehicle: Standard  
- Minivan  
- Van: Cargo  
- Van: Passenger  
- Special purpose vehicle

---

## 🔧 Engine Size

- Total displacement of all engine cylinders in litres (L)

---

## 🔩 Cylinders

- Number of engine cylinders

---

## ⚙️ Transmission

| Code | Description                               |
|------|-------------------------------------------|
| A    | Automatic                                 |
| AM   | Automated Manual                          |
| AS   | Automatic with Select Shift               |
| AV   | Continuously Variable Transmission (CVT)  |
| M    | Manual                                     |
| 1–10 | Number of gears or speeds (e.g., 6 = 6-speed) |

---

## ⛽ Fuel Type

| Code | Description        |
|------|--------------------|
| X    | Regular Gasoline   |
| Z    | Premium Gasoline   |
| D    | Diesel             |
| E    | Ethanol (E85)      |
| N    | Natural Gas        |

---

## 🛣️ Fuel Consumption (L/100 km)

- **City**: Urban stop-and-go driving  
- **Highway**: Open highway and rural driving  
- **Combined**: 55% city + 45% highway driving

---

## 🌱 CO₂ Emissions

- Tailpipe CO₂ emissions in grams per kilometre (g/km), based on combined city and highway driving  
- For Plug-in Hybrid Electric Vehicles (PHEVs), reflects a mix of electric and gasoline operation

---

## 📊 CO₂ Rating

- Rated from **1 (worst)** to **10 (best)** based on tailpipe CO₂ emissions
