# Project-_4
Project 4 <br>

Group 7 Members:<br>
Yenori Alvarez<br>
Patricia Ferreira<br>
Adrian Manalo<br>
Johana Mekwinski<br>

Proposal:<br>
We propose to analyze a stroke prediction dataset to identify key risk factors and develop a predictive model for stroke occurrence. By leveraging machine learning techniques, we aim to uncover insights that can inform preventive strategies and improve healthcare interventions for stroke patients.<br>

Source:<br> 
https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset<br>

Tableau Page:
https://public.tableau.com/views/Project4_17095655267460/StrokePrediction?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link

Tableau Page:<br>
Tableau was used to create visuals to help our group better understand the data and how it can be used.

Code:<br>
stroke.ipynb <br>
    - used to clean the stroke_data.csv; <br>
    - null_values: bmi, 201<br>
    - duplicate_ids: 0<br>

Creating model:<br>
    -used train_test_split, StandardScaler from sklearn
    -used tensoflow
    -converted categorical date to numerical with pd.get_dummies
    -split the processed data into features and target arrays
    -used standardscaler to standardize data
    -created a sequential model with 2 hidden layers to maximize efficency on first model
    
