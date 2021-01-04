# Patient-Treatement-Classification
Patient Care - Inside_Hospital & Outside_Hospital 


### Context

 In hospitals, medical treatments and surgeries can be categorized into inpatient and outpatient procedures. For patients, it is important to understand the difference between these two types of care, because they impact the length of a patient’s stay in a medical facility and the cost of a procedure. 

### In-patient Care (In-care Patient) and Out-patient Care (Out-care Patient)

  >>> The difference between an in-patient and out-patient care is how long a patient must remain in the facility where they have 
        the procedure done.
    
  >>> In-patient care requires overnight hospitalization. Patients must stay at the medical facility where their procedure was 
        done (which is usually a hospital) for at least one night. During this time, they remain under the supervision of a nurse or 
        doctor.

   >>> Patients receiving outpatient care do not need to spend a night in a hospital. They are free to leave the hospital once the 
        procedure is over. In some exceptional cases, they need to wait while anesthesia wears off or to make sure there are not any
        complications. As long as there are not any serious complications, patients do not have to spend the night being supervised. 
        [source of information: pbmhealth]



In this Classification Prediction Problem, I have used following modeling techniques as - 
  
  1. Logistic Regression,
    
  2. Random Forest, 
 
  3. Support Vector Machine,  
    
  4. K-NN Classifier, 
  
  5. Scalar like Standard & Quantile Transformer, 
    
  6. Feature Selection - (1) from scikit-learn & (2) Boruta Feature Selector, and
    
  7. GridSearchCV for parameter tuning.

After experimenting with data and applying differnt models, I finally landed upon Random Forest as best fitted model for Patient Treatment Classification with Accuracy Score 77.34 and F1_score is 67.25.

For Details please read my Jupyter file here.

Dataset Link - 

Train_data : https://raw.githubusercontent.com/dphi-official/Datasets/master/patient_treat_class/training_set_label.csv
               
Test_data : https://raw.githubusercontent.com/dphi-official/Datasets/master/patient_treat_class/testing_set_label.csv 
