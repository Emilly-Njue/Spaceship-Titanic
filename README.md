# **Spaceship-Titanic**

### File and Data Field Descriptions

train.csv - Personal records for about two-thirds (~8700) of the passengers, to be used as training data.<br>
PassengerId - A unique Id for each passenger. Each Id takes the form gggg_pp where gggg indicates a group the passenger is travelling with and pp is their number within the group. People in a group are often family members, but not always.<br>
HomePlanet - The planet the passenger departed from, typically their planet of permanent residence.<br>
CryoSleep - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.<br>
Cabin - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard.<br>
Destination - The planet the passenger will be debarking to.<br>
Age - The age of the passenger.<br>
VIP - Whether the passenger has paid for special VIP service during the voyage.<br>
RoomService, FoodCourt, ShoppingMall, Spa, VRDeck - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.<br>
Name - The first and last names of the passenger.<br>
Transported - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.<br>
test.csv - Personal records for the remaining one-third (~4300) of the passengers, to be used as test data. Your task is to predict the value of Transported for the passengers in this set.<br>
sample_submission.csv - A submission file in the correct format.
PassengerId - Id for each passenger in the test set.<br>
Transported - The target. For each passenger, predict either True or False.
