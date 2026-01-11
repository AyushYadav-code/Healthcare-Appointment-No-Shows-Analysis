Healthcare Appointment No-Show Prediction
- Project Overview :
- Missed medical appointments (no-shows) are a major challenge for healthcare providers, leading to wasted resources and inefficiencies.
- This project analyzes patient appointment no-show behavior using historical healthcare data and presents actionable insights through an interactive Power BI dashboard.

> Objectives :
- Analyze patterns behind patient appointment no-shows.
- Identify key factors affecting attendance (weekday, SMS reminders, waiting days, etc.)
- Build an interactive dashboard for decision-making.
- Provide insights to help reduce no-show rates.

> Dataset :
Name: Medical Appointment No Shows Dataset
Source: KAGGLE
Description: Contains patient demographics, appointment dates, SMS reminders, and attendance status

-- Key Columns :
ScheduledDay – Date appointment was scheduled.
AppointmentDay – Actual appointment date.
Age – Patient age.
Gender – Patient gender.
SMS_received – SMS reminder sent (0/1).
No-show – Appointment missed or not.
WaitingDays – Gap between scheduling and appointment.
Appointment Weekday – Day of the week (engineered).

> Tools & Technologies
Python (Pandas, NumPy) – Data cleaning & feature engineering.
Power BI – Interactive dashboard & visual analytics
Jupyter Notebook – Data preprocessing
MS Word / PDF – Project documentation

> Dashboard Features :
- KPI cards:
- Total Appointments.
- Total No-Shows.
- Show Rate (%).
- No-Show Rate (%).
- Day-wise performance table (Monday–Sunday).
- Sparkline trends inside tables.
- Impact of SMS reminders.
- Waiting days vs no-show trend.
- Interactive slicers & button-style filters.

 > Key Insights :
- SMS reminders significantly reduce appointment no-shows.
- Longer waiting periods increase the probability of no-shows.
- Certain weekdays show higher no-show rates.
- Patient behavior patterns can help optimize scheduling.

 > Prediction Objective :
- The goal of this project is to predict whether a patient will miss a scheduled medical appointment based on historical appointment data.

The model predicts:
- 1 → Patient will NOT show up
- 0 → Patient will show up

> Recommendations :
- Increase SMS reminders for high-risk patients
- Reduce waiting time between scheduling and appointment
- Optimize appointment slots based on weekday trends
- Use predictive analytics to flag potential no-shows
