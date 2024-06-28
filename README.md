## Traffic Accident Severity Analysis and Prediction

### Project Overview

This project analyzes traffic accident data to identify patterns related to road conditions, weather, and time of day. The goal is to visualize accident hotspots and contributing factors and use machine learning models to predict accident severity.

### Dataset

The dataset contains various attributes related to traffic accidents, such as:
- (List of attributes)

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
  
