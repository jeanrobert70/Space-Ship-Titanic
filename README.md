Predicting Which Passengers were Transported¶
This notebook looks into using various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting which passengers of Space Ship Titanic were transported by the anomaly using personal records recovered from the spaceship’s damaged computer system.

1. Problem Definition
Spaceship titanic collided with a spacetime anomaly. Half the passengers were transported to an alternate dimension. Given the spaceship's manifest of almost 13,000 passengers, can we predict which passengers were transported to the alternate dimension?

2. Data
The data is from Kaggle's Spaceship Titanic competition and was downloaded as a csv file from the following link: https://www.kaggle.com/competitions/spaceship-titanic/data

3. Evaluation
Submissions are evaluated based on their classification accuracy, the percentage of predicted labels that are correct.

4. Features
Data Dictionary

PassengerId - A unique Id for each passenger. Each Id takes the form gggg_pp where gggg indicates a group the passenger is travelling with and pp is their number within the group. People in a group are often family members, but not always.

HomePlanet - The planet the passenger departed from, typically their planet of permanent residence.

CryoSleep - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.

Cabin - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard.

Destination - The planet the passenger will be debarking to.

Age - The age of the passenger.

VIP - Whether the passenger has paid for special VIP service during the voyage.

RoomService, FoodCourt, ShoppingMall, Spa, VRDeck - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.

Name - The first and last names of the passenger.

Transported - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.
