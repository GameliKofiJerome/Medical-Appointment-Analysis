# Medical-Appointment-Analysis
Data analysis on medical appointments of patients

## Objective of Analysis
A patient makes a doctor's appointment, receives all necessary instructions, and does not show up. What factors are to blame for this?
We will analyze the reasons why some patients do not show up for their medical appointments and whether there are reasons for that using the data we have in this notebook.
We will try to find some correlation between the different attributes we have and whether the patient shows up or not. The dataset we are going to use contains 110527 medical appointment records and its 14 associated variables (`PatientId, AppointmentID, Gender, ScheduledDay, AppointmentDay, Age, Neighbourhood, Scholarship, Hypertension, Diabetes, Alcoholism, Handcap', SMS_received, No-show`). Among these variables, there are 13 independent variables  and one dependent variable which is  `No-show`.

## Questions to be answered by the analysis:
- What is the percentage of no-shows?
- What important factors will enable us to predict if a patient will show up for their scheduled appointment?
    - Is the gender of the patient related to whether a patient will show or not?
    - Are patients with scholarships more likely to miss their appointments?
    - Are patients who don't receive SMS more likely to miss their appointment?
    - Is the time difference between the scheduling and appointment related to whether a patient will show up?
    - Does age affect whether a patient will show up or not?
    - What is the percentage of patients missing their appointments for every neighbourhood?
