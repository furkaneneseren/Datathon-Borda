# Datathon-Borda

## Goal of the Competition
The goal of this competition is to predict the duration of a surgery. You will create a regression model trained on labeled data extracted from Borda Technology's IoT sensor and Borda Technology's database. The evaluation metric for this competition is __RMSE__

Competition Link: [Kaggle](https://www.kaggle.com/competitions/prediction-of-surgery-duration)

## Dataset Description

### Files
- train.csv - the training set
- test.csv - the test set
- sample_submission_.csv - a sample submission file in the correct format

### Columns
- DiagnosticICD10Code
The ICD-10-CM (International Classification of Diseases, Tenth Revision, Clinical Modification) is a system used by physicians and other healthcare providers to classify and code all diagnoses, symptoms and procedures recorded in conjunction with hospital care in the United States.
[ICD10](https://www.icd10data.com/ICD10CM/Codes)

A00-B99 Certain infectious and parasitic diseases
C00-D49 Neoplasms
D50-D89 Diseases of the blood and blood-forming organs and certain disorders involving the immune mechanism
E00-E89 Endocrine, nutritional and metabolic diseases
F01-F99 Mental, Behavioral and Neurodevelopmental disorders
G00-G99 Diseases of the nervous system
H00-H59 Diseases of the eye and adnexa
H60-H95 Diseases of the ear and mastoid process
I00-I99 Diseases of the circulatory system
J00-J99 Diseases of the respiratory system
K00-K95 Diseases of the digestive system
L00-L99 Diseases of the skin and subcutaneous tissue
M00-M99 Diseases of the musculoskeletal system and connective tissue
N00-N99 Diseases of the genitourinary system
O00-O9A Pregnancy, childbirth and the puerperium
P00-P96 Certain conditions originating in the perinatal period
Q00-Q99 Congenital malformations, deformations and chromosomal abnormalities
R00-R99 Symptoms, signs and abnormal clinical and laboratory findings, not elsewhere classified
S00-T88 Injury, poisoning and certain other consequences of external causes
U00-U85 Codes for special purposes
V00-Y99 External causes of morbidity
Z00-Z99 Factors influencing health status and contact with health services

- SurgeryGroup
Indicates risk score of surgery. Risk score decreases from A to E. "0" values can be interpreted as "NULL".

- AnesthesiaType
There are three types of anesthesia: general, regional, and local. Sometimes, a patient gets more than one type of anesthesia. The type(s) of anesthesia used depends on the surgery or procedure being done and the age and medical conditions of the patient.

- SurgeryName
Name of surgery

- Age
Age of patient

- Sex
Sex of patient

- Service
Medical department of the hospital

- DoctorID
Unique id for doctors

- AnaesthetistID
Unique id for anaesthetist

- ElapsedTime(second)
Target variable duration of surgeries
