## AirBnb

****Introduction****: 
                  A hotel is a managed building or establishment, which provides guests with a place to stay overnight – on a short-term basis – in exchange for money. 
                  Due to the modern internet revolution, the reservation of a room in any hotel can be made via online by using the Online Travel Agents (OTA). 
                  These agents create search engine applications that acts as middle man between the hotel merchants and customers to process direct online reservations.
                  An OTA acts as commission-free direct bookings agent for the customers; also provide the way to optimize the merchant’s sales strategy and
                  maximize profit. These agents take an average commission fee from merchants between 10% to 25% after each successful stay of the customers.
                  From the article „‟US Hotel gross booking by OTA with the comparison hotel applications /websites” released by „The wall Street Journal‟ , 
                  the country “United States of America” have started to make higher turnover from the F.Y(Financial Year)-2016. By the F.Y-2017, 
                  the gross booking by OTA agents made $34.8 billion (B) and whereas the hotel websites/apps made only $32.4B.
                  The key advantages of having the hotel business in OTA platforms are Increased Exposure (Visibility), Drive Traffic, More Bookings, Right Guests,
                  Better Rankings and Better Reviews.
                  
****Problem Statement****
**1.Business Problem Understanding:**
AirBnB is one such OTA platform acts as the middle man between hotels and customers to book a room; also provides lodging, homestays for vacations and tourism activities.The platform provides businesses an increased opportunity to reach out to a wider customer base and at the same time it empowers the customer by providing them with beforehand details of the type of the property, amenities, location of stay and plan out their budget for the trip accordingly. The major part of the OTA platform is to provide an accurate prediction of Cost Per Night to the customers.

**2.Business Objective:**
Cost Per Night: The total amount that end user has to spend for staying at a property for a single night is known as cost per night. There are various factors that determine the cost per night from property to property also depends upon features like quality of the property, its size, neighborhood, facilities/amenities and location
Travelers often budget their travel costs in order to ensure that they spend only the optimal amount and knowing cost per night beforehand would help them plan their travel efficiently. This helps the OTA platforms by providing a comparison benchmark between properties and also help in identifying the various features of a property that will determine the cost per night. This information will also help the host/owners of a property in identifying the short coming of their property and help improve their properties by matching facilities/amenities provided by their competitors.

**OBJECTIVE:** The objective is to predict the price of the rooms per night in LA.

**DATA PREPROCESSING:** * Modify the appropriate data types of the features. * Null values treatment. * Handling the anomolies. * Outlier Treament * Handling cardinality issue * Feature Engeneering and Feature Extraction - such as Encoding, Transformation, Scaling and Creating new features

**STATISTICAL ANALYSIS:** For Numerical vs Numerical normality test: SpearMan Correlation test, for Categorical vs Numerical normality test: Kruskal-Wallis test to check for dependency. As the target variable is not normal non linear tests are used. 

**Model Building:** Linear Regression (Checked for linear assumptions), Decission Tree Regression, Random Forest Regression, Ada-Boosting Regressor, Gradient Boosting Regressor, XG Boosting Regressor,  Light Gradient Boosting Regressor, CAT Boosting Regressor

**Model Evaluation:** Mean square error, Root Mean Square error 

**Hyperparameter Tuning:** GridSearch CV 

**Feature Selection:** Forword feature selection, Backword feature Selection
