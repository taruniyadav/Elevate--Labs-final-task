#  Healthcare Appointment No-Show Prediction

This project analyzes healthcare appointment data to predict whether a patient will show up for their appointment, using machine learning and data visualization techniques. It also offers actionable recommendations to optimize scheduling and reduce no-shows.

---

##  Objective

To predict patient no-shows using a decision tree classifier and extract meaningful insights from appointment trends through Power BI dashboards.

---

##  Tools & Technologies

- **Python** – Pandas, NumPy, Scikit-learn
- **Jupyter Notebook** – Data processing and model training
- **Power BI** – Visual dashboard and insights
- **Excel** – Source data for appointments

---

##  Project Workflow

1. **Data Import & Cleaning**
   - Loaded the dataset from Excel
   - Cleaned and preprocessed fields (dates, binary values, etc.)

2. **Exploratory Data Analysis (EDA)**
   - Visualized trends in patient no-shows based on age, gender, SMS reminders, etc.

3. **Feature Engineering**
   - Converted date columns to datetime
   - Created weekday features, calculated wait time

4. **Model Building**
   - Trained a **Decision Tree Classifier** using scikit-learn
   - Evaluated performance using accuracy, confusion matrix

5. **Power BI Dashboard**
   - Designed an interactive dashboard to show:
     - No-shows by age, gender, day, and neighborhood
     - Effect of SMS and scholarships on show-up rates
     - No-show rate over time

6. **Optimization**
   - Proposed strategic recommendations based on insights and model outputs

---

##  Results

- **Key Finding:** SMS reminders and appointment day significantly impact no-show rates

---

##  Power BI Dashboard

The dashboard highlights patterns in appointment behavior. It includes  bar charts, and slicers to filter by gender, neighborhood, SMS received, etc.

 See insights in `PowerBI_Dashboard.pbix`.

---

##  Optimization Recommendations

View detailed recommendations here:  
[ Optimization_Recommendations.md](./Optimization_Recommendations.md)

---

##  How to Run

1. Clone this repo
2. Open `medical_no_show.ipynb` to view the Python analysis
3. Open `medical no shows.xlsx` in Power BI to recreate the dashboard
4. View `README.md` and `Optimization_Recommendations.md` for documentation

---


