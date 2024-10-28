# Brazilian Medical Appointment Analysis

## Project Purpose 
The followng analysis explores Brazilian health data on 110K+ patients along with demographic information and whether or not they showed up for scheduled medical appointments. Reducing medical no-shows can ensure patients receive the medical care they need, and also reduces medical resource and financial waste.

### Dataset Description
The data can be found on kaggle: [Brazilian medical appointments dataset](https://www.kaggle.com/datasets/joniarroba/noshowappointments/discussion/29699#229356). Once at the webpage click on the download button and download the zip file to the local machine. The dataset consists of over 110K + records, 2 ID columns, 10 predictor variables, and the no-show column of interest.

   ### The following variables were found in the dataset:
      - PatientId: Identification of a patient
      - AppointmentID: Identification of each appointment
      - Gender: Male or Female
      - DataMarcacaoConsulta: The day of the actual appointment.
      - DataAgendamento: The day someone called or registered the appointment.
      - Age: Age of patient
      - Neighbourhood: Where the appointment takes place.
      - Scholarship: Yes or no
      - Hipertension: Yes or no
      - Diabetes: Yes or no
      - Alcoholism: Yes or no
      - Handicap: Yes or no
      - SMS_received: 1 or more messages sent to the patient.
      - No-show: Yes or no

## Questions for Analysis
1) Are differences seen in the no-show percentages between genders?
2) This dataset contains three months of data, are differences seen in the number of no-shows for any of these three months?
3) Are differences seen in the no-show percentages between various age cohorts?
4) Are there differences between gender no-shows in individuals who have a chronic health condition.

## Conclusions
### Findings Summary
1) Little to no difference exists between males and females as to whether or not they'll make their appointment. Around 20% of each gender misses appointments. Perhaps looking at gender in different neighborhoods or individually while exploring the age cohorts may result in greater differences.
2) There is a marked increase in the number of no-shows in May. If further data continues to support this observation, further investigation may be needed to determine the reasoning as to why and also to develop strategies to minimize such levels of no-shows.
3) Our age cohort analysis showed fluctuations between 20-25%. The highest percentage of around 25% occurred in lower age groups and then slowly decreased until 90+ when large variations occurred. I suspect this may be simply due to a small sample size. While I did not do so in this study, perhaps analyzing the age cohorts when individuals possess a chronic conditions is an additional area to explore.
4) Looking at differences in no-shows between genders when individuals have a chronic condition, a slight increase in female no-shows was observed. It was only around a .75% difference though. I would perhaps explore gender and chronically ill individuals.
   
### Limitations
1) The data only had three months of data. I would be interested in exploring larger time points to determine if seasonal differences exist as we saw for May.
2) I would like to break down the categorical chronic illnesses into degrees of severity. Is individual slightly hypertensive? How many drinks do they consumer per week versus yes or no for
alcoholism? This may allow for more robust correlation to be explored.
3) I would also like to explore income levels, educational levels, etc.
