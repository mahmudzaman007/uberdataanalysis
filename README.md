# 🚖 Uber NYC 2014 Ride Analysis with Simulated Gender Insights

This project explores Uber ride data from April to September 2014 in New York City. While the original dataset does not include demographic details, simulated gender data was introduced to uncover patterns in mobility behavior across time, space, and base stations.

---

## 📊 Project Highlights

- ✅ Merged & cleaned 6 months of Uber trip data
- ✅ Extracted key temporal features (hour, day, weekday, month)
- ✅ Simulated a gender column (50% Male / 50% Female)
- ✅ Created multiple visualizations:
  - Total rides by gender
  - Top 5 ride hours and Uber bases by gender
  - NYC ride locations by gender (Lat/Lon map)
  - Heatmaps showing ride volume by hour & weekday for each gender

---

## 🛠️ Tech Stack

- **Language:** Python 3
- **Libraries:** `pandas`, `matplotlib`, `seaborn`, `numpy`

---

## 📁 Dataset

Original Uber data source:
- 📂 [Uber NYC Data on Kaggle](https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city)

Files used:
- `uber-raw-data-apr14.csv`
- `uber-raw-data-may14.csv`
- `uber-raw-data-jun14.csv`
- `uber-raw-data-jul14.csv`
- `uber-raw-data-aug14.csv`
- `uber-raw-data-sep14.csv`

> ⚠ If your dataset is over 100MB, please store it on an external host like Google Drive and update the link here:
> 📎 [Download Uber NYC Dataset](https://drive.google.com/your-link)

---

## 📸 Sample Visualizations

| Total Rides by Gender | NYC Ride Map by Gender |
|-----------------------|------------------------|
| ![total rides](images/total_rides_by_gender.png) | ![map](images/gender_location_map.png) |

More plots:
- `top_5_hours_by_gender.png`
- `top_5_bases_by_gender.png`
- `heatmap_male.png`
- `heatmap_female.png`

---

## ▶️ Getting Started

1. Clone this repo:
```bash
git clone https://github.com/yourusername/uber-2014-analysis.git
cd uber-2014-analysis
