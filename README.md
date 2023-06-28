# Employee Attrition Prediction
Competition Task: Given factors influencing employee attrition and records of whether employees have resigned, build a model to predict employees who are likely to resign.

## Data Analysis Methods:
### 1. Exploring Data
### 2. Missing Value Checking
### 3. Visual Analysis using Pyecharts

![Screenshot 1](https://github.com/Starrywoof/Virtual-Scene-Modeling-of-Robot-with-OpenGL/blob/main/Pictures/Schematic_Diagram_of_Model_Construction.png)

![Screenshot 2](https://github.com/Starrywoof/Virtual-Scene-Modeling-of-Robot-with-OpenGL/blob/main/Pictures/Schematic_Diagram_of_Model_Construction.png)

![Screenshot 3](https://github.com/Starrywoof/Virtual-Scene-Modeling-of-Robot-with-OpenGL/blob/main/Pictures/Schematic_Diagram_of_Model_Construction.png)

*Visualization*

## Data Processing:
### 1. Single Feature Checking


### 2. Collinearity Analysis (Visualized using Heatmap)

![Screenshot 4](https://github.com/Starrywoof/Virtual-Scene-Modeling-of-Robot-with-OpenGL/blob/main/Pictures/Schematic_Diagram_of_Model_Construction.png)

*Heatmap*

### 3. One-Hot Encoding



## Additional Processing:
### 1. Data Standardization: Removing unit limitations and transforming data into dimensionless numeric values.

### 2. Feature Engineering:
- Combining the "YearsWithCurrManager" feature with "TotalWorkingYears"
- Combining "JobSatisfaction," "EnvironmentSatisfaction," and "RelationshipSatisfaction" features
- Removing "JobLevel" and "YearsWithCurrManager" features.

### 3. Data Segmentation: Segmenting data related to age and salary.

## Model Construction:
- Random Forest: Accuracy of 0.876***
- Support Vector Machine: Accuracy of 0.879***
- Logistic Regression: Accuracy of 0.902857

## Results:
The logistic regression model achieved an accuracy of 0.90285 and ranked 13th out of 269 teams in the Data Castle Data Mining Competition.