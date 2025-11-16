# Hospital_Bed_Availablity
🏥 Hospital Bed Availability Prediction

This project predicts how many hospital beds will be available based on patient demand, staff details, and weekly hospital activity.
The data is synthetic and created only for learning and analysis.

📂 Dataset Used

staff.csv – Hospital staff information
staff_schedule.csv – Weekly staff schedule
services_weekly.csv – Weekly service activity
patients.csv – Patient details and satisfaction

🎯 Goal

To study hospital operations and build a model that can predict bed availability to help with resource planning.

⚙️ Tools & Libraries

Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn

📊 What the Project Does

Cleans and merges multiple datasets
Performs EDA (heatmap, boxplot, pairplot)
Trains Linear and Lasso Regression models
Predicts weekly available beds
Saves output plots and results in the outputs/ folder

📁 Output Files (Saved Separately)

All important results are saved in the outputs folder:
actual_vs_predicted.png
weekly_trend.png
correlation_heatmap.png
pairplot.png
boxplot.png
prediction_results.csv

🧠 User Input

At the end of the notebook, you can enter:
week
month
patient requests
patient admitted
average satisfaction
average age
And the model will predict available beds.
