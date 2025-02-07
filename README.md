# Hotel_Booking_Cancellation_Prediction
This project aims to predict whether a hotel booking will be canceled based on various features related to booking details, customer preferences, and hotel-related factors. The prediction can help hotels optimize their resources, manage cancellations, and improve customer satisfaction.


---

**Table of Contents**

- **Overview**


- **Dataset**


- **Features**


- **Objective**


- **Data Preprocessing**


- **Modeling**


---


**Overview**


Hotel cancellations can significantly affect business operations, leading to revenue losses and resource mismanagement. This project uses machine learning techniques to predict booking cancellations, helping hotels plan better and reduce losses.

---


**Dataset**


The dataset consists of the following features:


**no_of_adults:** Number of adults included in the booking


**no_of_children:** Number of children included in the booking


**no_of_weekend_nights:** Number of weekend nights included in the booking


**no_of_week_nights:** Number of week nights included in the booking


**type_of_meal_plan:** Meal plan chosen by the customer


**required_car_parking_space:** Whether a car parking space is required (0 or 1)


**room_type_reserved:** Room type reserved by the customer


**lead_time:** Number of days between booking and arrival


**arrival_year:** Year of arrival


**arrival_month:** Month of arrival


**arrival_date:** Date of arrival


**market_segment_type:** Market segment classification (e.g., Corporate, Online)


**repeated_guest:** Whether the guest is a repeated customer (0 or 1)


**no_of_previous_cancellations:** Number of previous cancellations by the customer


**no_of_previous_bookings_not_canceled:** Number of previous successful bookings


**avg_price_per_room:** Average price per room for the booking


**no_of_special_requests:** Number of special requests made by the customer


**booking_status:** Target variable (Canceled or Not Canceled)


---


**Objective**


The main objective is to build a machine learning model to predict whether a booking will be canceled based on the provided features.


---


**Data Preprocessing**


The following preprocessing steps were performed:


- Handling missing values
- Encoding categorical variables (type_of_meal_plan, room_type_reserved, market_segment_type, repeated_guest, and required_car_parking_space)
- Scaling numerical features (lead_time, avg_price_per_room, etc.)
- Splitting the dataset into training and testing sets

---

**Modeling**


The following models were used for prediction:


- KNeighborsClassifier
- DecisionTreeClassifier
- LogisticRegression
- StackingClassifier	
- RandomForestClassifier


---




