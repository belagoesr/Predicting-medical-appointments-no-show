# kaggle-predicting-no-show-appointments
This project uses the dataset https://www.kaggle.com/joniarroba/noshowappointments of medical appointments no-show. 

The purpose is to investigate which factors influences on a person missing an appointment as well as predict if a person will miss the appointment.

**Steps:**

**1 & 2. BI/Data understanding**

   - Does the waiting time until the appointment matter?
    
   - Does age matter?
    
   - Does miss an appointment before influences on missing again? 
    
**3. Data preparation**

   - Check for missing data
    
   - Clean data and engineer new features
    
   - One Hot Encode categorical variables

**4. Model Data**

   To solve the class imbalance of the dataset 2 approaches are investigated: 
    
   - use whole dataset to build a classifier
        
   - perform downsampling and upweight before building a classifier (based on https://developers.google.com/machine-learning/data-prep/construct/sampling-splitting/imbalanced-data)

**5. Results**

   - Choose best classifier based on a appropriate chosen metric


