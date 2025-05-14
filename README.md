# Food Service EDA Project

# Exploratory Data Analysis (EDA) on Food Waste and Operations

This project explores operational efficiency and food waste in a food service environment using a dataset that includes variables such as meals served, kitchen staff, environmental conditions, and waste categories. The goal is to uncover insights that can guide better staffing, reduce food waste, and improve decision-making.

## 📁 Dataset Overview

| Column Name       | Description                                                             |
|------------------|-------------------------------------------------------------------------|
| `ID`             | Unique identifier for each record                                       |
| `date`           | Date of observation                                                     |
| `meals_served`   | Number of meals served that day                                         |
| `kitchen_sta`    | Number of kitchen staff working                                         |
| `temperature_C`  | Temperature (in Celsius) on the recorded day                            |
| `humidity_percent` | Humidity percentage on the recorded day                              |
| `day_of_week`    | Day of the week (0 = Sunday, 6 = Saturday)                              |
| `special_event`  | Binary: 1 = Special Event, 0 = Normal Day                               |
| `past_waste_kg`  | Food waste from past days in kilograms                                  |
| `sta_experience` | Experience level of kitchen staff (Beginner, Intermediate, etc.)        |
| `waste_category` | Category of food waste (e.g., dairy, meat, etc.)                        |


# important outputs
- Medium staffing levels are associated with lower food waste
- Food waste increases significantly on special event days
- Humidity shows moderate correlation with food waste — may affect spoilage
- Positive correlation between meals served and food waste suggests overproduction risks

Looker Studio link: https://lookerstudio.google.com/reporting/78db20d6-c070-4746-85f4-0ea408b1bb74 
