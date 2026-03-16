
# Hotel Booking Cancellation Prediction

## Business Problem
Hotels lose revenue when guests cancel reservations close to their arrival date. The goal of this project was to build a predictive model that identifies bookings that are likely to cancel so the hotel can take preventive action.

## Dataset
The dataset contains over 119,000 hotel bookings from a Portuguese hotel chain. Each booking includes information about booking timing, stay details, deposit policies, and customer behavior.

## Analysis
Exploratory data analysis revealed several patterns related to cancellations:

- Guests who book far in advance are more likely to cancel
- Deposit requirements significantly reduce cancellation risk
- Customers with a history of cancellations tend to cancel again

These insights helped guide feature selection for the predictive model.

## Model
A Gaussian Naive Bayes model was trained using booking behavior features such as lead time, previous cancellations, and deposit type.

The model achieved approximately 76% accuracy when predicting booking cancellations.

## Business Recommendations
Based on the analysis and model results, the following actions are recommended:

1. Encourage prepaid or deposit-based bookings to reduce cancellation rates.
2. Send reminders or incentives to guests who book far in advance.
3. Monitor customers with a history of cancellations and require additional confirmation.

## Tools Used
- Python
- Pandas
- Scikit-learn
- Seaborn
- Google Colab



