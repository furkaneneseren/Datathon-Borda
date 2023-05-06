# Datathon-Borda (PREDICTION OF SURGERY DURATION)

## Goal of the Competition
The goal of this competition is to predict the duration of a surgery. You will create a regression model trained on labeled data extracted from Borda Technology's IoT sensor and Borda Technology's database. The evaluation metric for this competition is __RMSE__

Competition Link: [Kaggle](https://www.kaggle.com/competitions/prediction-of-surgery-duration)

## Dataset Description

### Files
- train.csv - the training set
- test.csv - the test set
- sample_submission_.csv - a sample submission file in the correct format

### Columns
- DiagnosticICD10Code: The ICD-10-CM (International Classification of Diseases, Tenth Revision, Clinical Modification) is a system used by physicians and other healthcare providers to classify and code all diagnoses, symptoms and procedures recorded in conjunction with hospital care in the United States. [ICD10](https://www.icd10data.com/ICD10CM/Codes)

- SurgeryGroup: Indicates risk score of surgery. Risk score decreases from A to E. "0" values can be interpreted as "NULL".

- AnesthesiaType: There are three types of anesthesia: general, regional, and local. Sometimes, a patient gets more than one type of anesthesia. The type(s) of anesthesia used depends on the surgery or procedure being done and the age and medical conditions of the patient.

- SurgeryName: Name of surgery

- Age: Age of patient

- Sex: Sex of patient

- Service: Medical department of the hospital

- DoctorID: Unique id for doctors

- AnaesthetistID: Unique id for anaesthetist

- ElapsedTime(second): Target variable duration of surgeries
