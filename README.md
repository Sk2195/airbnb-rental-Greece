# Airbnb Optimal Price Predictor for Athens, Greece
#  Athens, Greece – the site of our latest project – utilizes machine learning models to generate suggested listing Airbnb prices. To provide an accurate prediction, users must input data related to the property's attributes and its location.

# Features
# The model considers the following features for predictions:

# Minimum Nights
# Number of Reviews
# Reviews Per Month
# Calculated Host Listings Count
# Availability (365 days)
# Number of Reviews LTM (Last Twelve Months)
# Rating
# Bedrooms
# Beds
# Baths
# Minimum Displacement
# Nearest Stations (e.g., Ακρόπολη, Μοναστηράκι, Σύνταγμα)
# Neighbourhoods (e.g., ΑΚΡΟΠΟΛΗ, ΕΜΠΟΡΙΚΟ ΤΡΙΓΩΝΟ-ΠΛΑΚΑ)
# Property Types (e.g., Boutique hotel, Condo, Home)
# Room Types (e.g., Entire home/apt)
# Getting Started
# Setup:

Clone this repository.
Install the required packages:
Copy code
pip install -r requirements.txt
Running the Streamlit App:

Once you've set everything up, you can run the Streamlit app:
arduino
Copy code
streamlit run app.py
Usage:

Open the provided link in your browser.
Input the values for the given features.
Click on 'Predict' to get the optimal price for the Airbnb listing.
Model Details
The model has been trained on historical Airbnb data from Athens, Greece. A RandomForestRegressor was used for the prediction due to its robustness and capability to handle non-linear data.

Future Improvements
Incorporate more granular location data for better accuracy.
Consider seasonality and special events which can influence prices.
Refine the model with more data and potentially explore more advanced algorithms.
