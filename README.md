## Traffic Accident Severity Analysis and Prediction

### Project Overview

This project analyzes traffic accident data to identify patterns related to road conditions, weather, and time of day. The goal is to visualize accident hotspots and contributing factors and use machine learning models to predict accident severity.

### Dataset

The dataset contains various attributes related to traffic accidents, such as:

Time: The time when the accident occurred.
Day_of_week: The day of the week.
Age_band_of_driver: The age group of the driver.
Sex_of_driver: The gender of the driver.
Educational_level: The educational level of the driver.
Vehicle_driver_relation: The relationship of the driver to the vehicle (e.g., owner, employee).
Driving_experience: The driving experience of the driver.
Type_of_vehicle: The type of vehicle involved in the accident.
Owner_of_vehicle: The owner of the vehicle.
Service_year_of_vehicle: The service years of the vehicle.
Accident_area: The area where the accident occurred.
Lanes_or_Medians: Information about lanes or medians.
Road_allignment: The alignment of the road.
Types_of_Junction: Types of junctions.
Road_surface_type: The type of road surface.
Road_surface_conditions: The condition of the road surface.
Light_conditions: The light conditions at the time of the accident.
Weather_conditions: The weather conditions at the time of the accident.
Type_of_collision: The type of collision.
Number_of_vehicles_involved: The number of vehicles involved.
Number_of_casualties: The number of casualties.
Vehicle_movement: The movement of the vehicle.
Casualty_class: The class of casualty.
Sex_of_casualty: The gender of the casualty.
Age_band_of_casualty: The age group of the casualty.
Casualty_severity: The severity of the casualty.
Work_of_casuality: The work status of the casualty.
Fitness_of_casuality: The fitness status of the casualty.
Pedestrian_movement: The movement of pedestrians involved.
Cause_of_accident: The cause of the accident.
Accident_severity: The severity of the accident.


### Analysis Plan

1. **Time of Day Analysis**:
   - Distribution of accidents by time of day.
   - Correlation between time of day and accident severity.

2. **Day of Week Analysis**:
   - Distribution of accidents by day of the week.
   - Correlation between day of the week and accident severity.

3. **Road Conditions Analysis**:
   - Distribution of accidents by road conditions.
   - Correlation between road conditions and accident severity.

4. **Weather Conditions Analysis**:
   - Distribution of accidents by weather conditions.
   - Correlation between weather conditions and accident severity.

5. **Accident Hotspots Visualization**:
   - Geographic visualization of accident locations (if location data is available).
   - Identification of accident hotspots.

6. **Contributing Factors Analysis**:
   - Analysis of common causes of accidents.
   - Correlation between various factors (e.g., driver age, vehicle type) and accident severity.

### Machine Learning Models
we just use
- Random Forest


### Model Evaluation

Each model was evaluated using cross-validation and tested on the test set. The evaluation metrics include:
- Cross-validation mean accuracy
- Test set accuracy
- Classification report
- Confusion matrix

### Results

- **Random Forest**:
  - Test set accuracy: 84%
  
