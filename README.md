# shivam-infotek-attendance-predictor
Predicts the employee strength likely to join office on a given working day.


In many companies, employees provide food, transport and parking space in the office. Each employee has to mark daily attendance after coming to office. If we could predict the employee strength likely to be present in office on a given day, employers can properly plan the resources and reduces the cost significantly. 

The Attendance strength depends on number of factors like 
Planned leave
Unplanned leaves
Work from home 
Vacation clubbed with the bank holidays  
Weather Conditions
Many times, specific teams in organization follow the client calendar adding to uncertainty

If we could develop a predictive system to forecast employee strength to work from office on a given day, employers can plan the following resources effectively and save the cost

Data

1. TrainingData1.csv contains the following columns
	1. Month: - Values from 1 to 12 representing months of years
	2. Day: Day of the month (1-31)
	3. Day of Week: (2-6) (Monday to Friday)
	4. Holiday: (0-1) , whether a particular day is holiday
	5. Holiday Weightage: percentage of employees for which a day is holiday
	6. NearHoliday: If a day falls adjacent to holiday
	7. AttendancePercentage:- percentage of employees attending office

2. DevelopmentData.csv has same structure as mentioned above.

Solution:-
I have developed a Jupyter Notebook Resource_Utilization_Predictor-1.0.ipynb, which mainly contains 
	EDA  
	ANN based Predictions models with various HyperParameters
