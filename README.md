# Investigate-Dataset-NoShowAppointment
This dataset contains information of 100k medical appointments in Brazil and is focused on the question of 
- Whether or not patients show up for their appointment.
- What factors determines if patient showup for appointments
- Does gender influence patient showing up for appointments
- Does having patient schlolarship determines if patient show up or not

The following are initial columns in the dataset.
-PatientID - Indicates ID for each patient
- AppointmentID - Indicates ID for each appointment made
- ScheduledDay - Tells us on what day the patient set up their appointment.
- Neighborhood - Indicates the location of the hospital.
- Scholarship - Indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
- SMS_recieved - Indicates message sent to the patient
- No_show - Indicates if the patients was present for appointment or not. No (means patient showed up), YES (means patient did not show up)

Based on the findings generated from the research questions, and taking into consideration the limitations, it was found out that
- Out of the total number of patients which was recorded at 110526 after cleaning of the data, 22319 patients did not show up for their appointments
- 2.79924 (80.2%) patients do not have scholarship but showed up for their appointments
- 19741(19.8%) patients do not have scholarship and did not show up for their appointments
- 8283 (76.3%) patients have scholarship and showed up for their appointments
- 5.2578(23.7%) patients have scholarship but did not show up for their appointments
- It was noted that scholarship does not have positive effects on patients showing up for their appointments
- It was also noted that more females registered for appointment more than the male counterparts, but the females did not show up for their appointments mre than their male counterparts

Limitations of the analysis

Correlation between No_show and scholarship was not defined in the analysis The study does not include whether SMS recieved have impact on patients showing up for their appointments
