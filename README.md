# Diabetes-Prediction

The dataset contains data from the US Health Facts Database, which comprised de-identified diabetes patients between 1999 and 2008

Features and their types Encounter ID: Numeric

Patient number: Numeric

Race: Nominal

Gender: Nominal

Age: Nominal

Weight: Numeric

Admission Type: Nominal

Discharge disposition: Nominal

Admission source: Nominal

Time in hospital: Numeric

Payer code: Nominal

Medical specialty: Nominal

Number of lab procedures: Numeric

Number of procedures

Number of medications: Numeric

Number of outpatient visits: Numeric

Number of emergency visits: Numeric

Number of inpatient visits: Numeric

Diagnosis 1: Nominal

Diagnosis 2: Nominal

Diagnosis 3: Nominal

Number of diagnoses: Numeric

Glucose serum test result: Nominal

A1c test result: Nominal

Change of medications: Nominal

24 features for medications (metformin, repaglinide, nateglinide, chlorpropamide, glimepiride, acetohexamide, glipizide, glyburide, tolbutamide, pioglitazone, rosiglitazone, acarbose, miglitol, troglitazone, tolazamide, examide, sitagliptin, insulin, glyburide-metformin, glipizide-metformin, glimepiride-pioglitazone, metformin-rosiglitazone, and metformin-pioglitazone): Nominal

Diabetes medications: Nominal

Readmitted: Nominal

For more details about the features click: https://www.hindawi.com/journals/bmri/2014/781670/tab1/

The classification target in this problem is the variable "readmitted"

in the dataset, it consists of 3 factors:

"NO": for no record of readmission
">30": if the patient was readmitted in more than 30 days
"<30": if the patient was readmitted in less than 30 days
We are interested in predicting if a patient should be readmitted in less than 30 days.

