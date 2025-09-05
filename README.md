# Task 04 - Traffic Accident Analysis & Hotspots

**Internship:** Data Science Internship at SkillCraft Technology  
**Intern:** Ishika Arora

---

## 🎯 Objective
Analyze traffic accident data to identify patterns related to weather conditions, road conditions, time of day, and visualize accident hotspots.

---

## 📂 Dataset
- **Source:** (e.g., Kaggle / US Accidents dataset)  
- **Note:** The raw dataset is large and intentionally **not included** in this repo. Download the dataset from the original source and place it as `US_Accidents_March23.csv` if you want to run the notebook locally.

---

## ⚙️ What I did
1. Loaded the US Accidents dataset and parsed `Start_Time` into datetime.  
2. Extracted time features (Hour, DayOfWeek).  
3. Visualized:
   - Top weather conditions for accidents.  
   - Accident distribution by day of week and hour.  
   - Accident severity distribution.  
4. Built an interactive **heatmap of accident hotspots** and saved it as `US_Accidents_March23.html`.

