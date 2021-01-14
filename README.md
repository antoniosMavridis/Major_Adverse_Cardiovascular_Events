# Major_Adverse_Cardiovascular_Events
Prediction and 10-year Risk Assessment of Major Adverse Cardiovascular Events using Machine Learning Techniques

## Introduction
Major Adverse Cardiovascular Events (MACE) are
defined as the occurrence of any episode including death, stroke,
thromboembolic event, acute myocardial infarction and stent
thrombosis or target lesion revascularisation. The prediction
of major adverse cardiac events (MACE) could play an essential
role in supporting clinical decisions that allow timely intervention
for preventable and treatable complications. It could also allow
management of low-risk patients without unnecessary admissions, investigations and monitoring. The risk models have played
an important role in primary prevention and are often used
in everyday clinical practice.  This work proposes machine
learning techniques for estimating a 10-year prediction of major
adverse cardiovascular event. Supervised learning algorithms
and classifiers such as Decisions Tree, Logistic Regression, KNearest Neighbors and Support Vector Machine (SVM) are used
to differentiate a healthy patient from an unhealthy one. The
study also shows the comparison of these methods in classification
of patients.

<img src="stroke.jpg" width="1000" height="500" /> </br>

## Data Set Description
The dataset contains 3315 samples from patients with acute
first-ever ischemic stroke admitted between 1993 and 2016
within 24 hours after stroke onset and followed up for up
to 10 years. An extended set of parameters is prospectively
registered for each patient including demographics, medical history, vascular risk factors, previous treatment, stroke
severity at admission, laboratory results, imaging data, inhospital treatment and medication at discharge. Patients are
followed up prospectively at the outpatient clinic at 1, 3 and 6
months after hospital discharge and yearly thereafter for up
to 10 years or until death. More specifically, it is divided
into 49 independent variables, mainly important factors that
are associated with the occurrence of a MACE, and two
dependent variables that provide the ground truth concerning
the occurrence of a MACE. In our study we focused on
the dependent variable named “MACE 10years”. The dataset
contains three different data types (String, Integer, Float).
Columns that contain numerical values as string representations are transformed in the appropriate numerical data type.
On the other hand, columns that contain categorical values
as integer representations are transformed in the appropriate
categorical data type. 
