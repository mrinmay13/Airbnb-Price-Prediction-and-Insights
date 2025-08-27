🏠 Airbnb Price Prediction and Insights

📌 Overview
This project focuses on predicting the price of Airbnb listings using machine learning techniques. By analyzing various factors such as property type, room type, location, number of reviews, and amenities, the goal is to:

- Build an accurate regression model to estimate listing prices
- Understand what features most influence pricing
- Help Airbnb hosts make data-driven decisions to optimize their revenue

---
🎯 Problem Statement
Pricing is a critical factor in the success of an Airbnb listing. Hosts often struggle to set competitive yet profitable prices. The objective of this project is to build a predictive model using available Airbnb listing data to:

- Predict the listing price for a given set of features
- Provide actionable insights into the most influential features affecting price

---

📊 Dataset
- **Name**: `Airbnb_data`
- **Source**: https://docs.google.com/document/d/1BhJoNJ9RgTgAHbAiOXh6tgTSjtuFkPox/edit?tab=t.0
- **Sample Features**:
  - `id`, `name`, `host_id`, `neighbourhood`, `latitude`, `longitude`
  - `room_type`, `property_type`, `minimum_nights`, `number_of_reviews`
  - `availability_365`, `amenities`, `host_is_superhost`, etc.
  - `price` (Target variable)

---
⚙️ Project Workflow

1. Data Exploration and Preprocessing (10 Marks)
- Analyze missing values, outliers, and feature distributions
- Clean and transform features (e.g., extract number of amenities)
- Convert categorical features using encoding techniques
- Feature scaling and standardization

2. Model Development (20 Marks)
- Split data into train, validation, and test sets
- Train various regression models:
  - Linear Regression
  - Random Forest Regressor
  - XGBoost Regressor
- Use grid search or randomized search for hyperparameter tuning

3. Model Evaluation (10 Marks)
- Evaluate model performance using:
  - **RMSE** (Root Mean Squared Error)
  - **MAE** (Mean Absolute Error)
  - **R² Score** (Coefficient of Determination)
- Visualize predictions vs actual prices

4. Final Report and Presentation (10 Marks)
- Create a 5-minute video summarizing the full project
- Discuss modeling approach, results, and business implications

---

✅ Success Criteria
- The model performs well on test data (reasonable RMSE and R²)
- Clear explanation of feature importance and pricing drivers
- Usable prediction outputs for new Airbnb listings
- Insights are actionable and relevant for non-technical stakeholders

---

🛠 Tools & Technologies
- **Languages**: Python
- **Libraries**:
  - `pandas`, `numpy` for data manipulation
  - `matplotlib`, `seaborn` for visualization
  - `scikit-learn` for modeling and evaluation
  - `XGBoost` for advanced regression
- **Environment**: Jupyter Notebook

---

📁 Project Structure (Recommended)
