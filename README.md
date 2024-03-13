# British-Airways-Job-Simulation

## Task 1: Web Scraping from Skytrax

BA_Scraping Jupyter Notebook contains a scraping code for collecting British Airways reviews from the Skytrax website. The analysis includes data cleaning, exploratory data analysis (EDA), and deriving insights to understand passenger sentiments and preferences.

### Data Analysis Steps:

- Scraping British Airways reviews from the Skytrax website.
- Conducting data cleaning.
- Performing exploratory data analysis.
- Visualizing insights with histograms, correlation matrices, etc.
- Analyzing review attributes such as seat comfort, cabin staff service, food & beverages, inflight entertainment, wifi & connectivity, ground service, value for money, recommendation status, and overall ratings.
  
Insights drawn from this analysis can be valuable for British Airways in improving the customer experience and enhancing overall satisfaction.

## Task 2: Booking Status Prediction Model

BA_PredictingModel Jupyter Notebokk contains a predictive model built to predict the booking status (whether a ticket will be booked or canceled) for British Airways customers. The model is implemented using the Random Forest Classifier algorithm.

### Features Used for Prediction:

- num_passengers: Number of passengers
- sales_channel: Channel through which the ticket is purchased
- trip_type: Type of trip (e.g., one-way, round trip)
- purchase_lead: Lead time between purchase and departure
- length_of_stay: Length of stay
- flight_hour: Hour of the flight
- flight_day: Day of the flight
- route: Flight route
- booking_origin: Origin of the booking
- wants_extra_baggage: Whether the customer wants extra baggage
- wants_preferred_seat: Whether the customer wants a preferred seat
- wants_in_flight_meals: Whether the customer wants in-flight meals
- flight_duration: Duration of the flight
- booking_complete: Whether the booking process is complete

### Feature Selection:

Feature importance scores were calculated to identify and eliminate unwanted features, simplifying the model while maintaining predictive performance.

### Conclusion:

This predictive model can be valuable for British Airways in predicting booking status and optimizing resource allocation and customer service based on predicted outcomes.

### Usage:

1. Clone this repository to your local machine.
2. Ensure you have Python installed along with necessary libraries (such as scikit-learn, pandas, numpy).
3. Run the provided Jupyter Notebook or Python script to train and evaluate the model.
4. Adjust parameters and features as needed for further optimization.
5. Use the trained model to make predictions on new data.
