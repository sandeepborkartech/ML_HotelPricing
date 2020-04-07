# ML_HotelPricing
To Run the project, please follow the steps give n below

1. Checkout the following four files
  1. ML_TEAM_4_Hotel_Data_Prep.ipynb
  2. ML_TEAM_4_Hotel_Price_predictor.ipynb
  3. ML_TEAM_4_Hotel_Model_Analysis_classification.ipynb
  4. ensorflow_for_Cancellation.ipynb
  5. hotel_bookings.csv
  
2. Once checked out. Run the ML_TEAM_4_Hotel_Data_Prep.ipynb in Jupyter notebook first. This file is the data exploration and prepartion
   step and it prepares and stores the data both regression and classification analysis.
3. Upon successful completion of the run of the above file, any of the other three files can be run
4. The ML_TEAM_4_Hotel_Price_predictor.ipynb predicts the ADR(Average daily rates or price per night) of a hotel using top 60 features
    that have been selected using Kbest method. The analysis and prediction is of regression type and the models used for this process are
    1. Linear Regression
    2. Lasso Regression
    3. SGD Regression
    4. Random Forest Regression
    5. Elastic Net
    6. Ada Boost Regression
    7. Support Vector Regression 
 5. The ML_TEAM_4_Hotel_Model_Analysis_classification.ipynb predicts the likelyhood of a booking cancellation using classification approach
 6. The models used are
    1.  K-Neighbors Classifier
    2. Logistic Regression
    3. Random Forest Classifier
    4. Support Vector Classifier
    5. Decision Tree Classifier
    6. Voting Classifier
 7. The final file Tensorflow_for_Cancellation.ipynb was yet another attempt to predict booking cancellation 
    using the power of neural nets
 8. The activation functions used are
    1. ELU
    2. RELU
    3. SELU
    4. Sigmoid
    5. TanH
 
Important instructions
1. All three analysis files are processor intensive. 
   and depending on the resource availibility of your computer(s) can take anywhere between 3-4 hours each.
2. Please make sure to run the three analysis file one at a time.
3. The most suitable configuration for running all file at the same time would be an 8-core hyperthreaded cpu with either a 4 core GPU 
   or an external eGPU and a minimum of 32GB RAM. It would still take atleast an hour to run all 3 files together.
4. Please note that all 4 files, store processed data, in pickle files at regular intervals. Please scan the code to check 
   where these checkpoints/pickle file creations are. You can simply continue from a checkpoint in case the process hangs or 
   your computer becomes unresponsive.
   
   Thank you!!!



    
