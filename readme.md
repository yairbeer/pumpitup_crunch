### Main features

1. Reading the data
2. Preprocessing:
    1. 2 stages of imputations. GPS_Height and then amount_tsh
    2. Recorded date parsing to year, weekday, week of the year, month, and age of well
    3. Labeling changed from strings to numbers (and back)
    4. Factorized str typed variables
3. Stratified cross validation
    1. Using custom accuracy function (nope, xgboost doesn't have one)
    2. Finding best number of rounds
    3. Create Full prediction trainset
