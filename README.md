# Patient No-Show Rates Analysis

## Introduction

"No-show" medical appointments indicate that a patient has not attended a scheduled appointment without giving any prior notification (within a set time 
limit, such as 24 hours in advance).

"No-shows" result in a loss of time and resources. Thus, reducing patient no-show rates is essential for improving the efficiency and effectiveness of 
healthcare providers, leading to better patient outcomes and continuity of care. (See: Marbouh D. et al., Evaluating the Impact of Patient No-Shows on 
Service Quality, Risk Management Healthcare Policy. 2020; 13: 509–517, available at: www.ncbi.nlm.nih.gov/pmc/articles/PMC7280239/)

To inform such efforts, this analysis aims to discover trends in patient no-show rates by looking at data from 110,527 medical appointments in Brazil in 
2015 and 2016.

The analysis will answer the following question:

* What factors are important to know to predict if a patient will show up for their scheduled appointment?

The data used in the analysis is available in a .csv file on www.kaggle.com.

## Conclusions

Based on the available data, we can conclude that the following factors are important to know to predict if a patient will show up for their scheduled 
appointment.

### Patient characteristics

- Gender

Women tend to have higher "no-show" rates than men and are over the average "no-show" rates. There does not appear to be a strong association between 
gender and attendance rates, however, women's no-show rates being only 2% higher than men's.

- Age

Younger people tend to have higher “no-show” rates, but again the difference appears small.

- Social support

Members of the Bolsa Familia social welfare program have 18% higher no-show rates. It's important to understand what obstacles to attending medical 
appointments beneficiaries of social support may face.

- Health condition: high blood pressure and diabetes

The "no-show" rates of patients with high blood pressure tend to be lower (by 19%) than those without high blood pressure. This requires further 
investigation but may be linked to high blood pressure being more widespread among older people and being a chronic condition requiring continuous care.

Similarly, patients with diabetes tend to have lower no-show rates (12% lower than patients without diabetes). This requires further investigation but 
like high blood pressure, it may be linked to the chronic nature of diabetes and the need for continuity of care.

- Disability

No strong association was found between disability and attendance rates. Patients with a disability, however, have a higher-than-average no-show rates. 
This requires further investigation into the accessibility and particular challenges persons with disabilities may face when accessing medical 
appointments (e.g. transportation issues).

- Repeat patients

The difference in the no-show rate between the repeat patients who missed their first appointment and those who didn't is substantial: 50%. This finding 
is important in showing that if a patient has one "no-show" appointment, this may be an indicator that they are more likely to miss another one. 
Additional measures may need to be taken for such patients to prevent repeat "no-shows".

- Alcoholism

There is no difference in-between the two groups. Both groups are at the overall average no-show rates.

- Frequency of appointment

Most "no-show" appointments are the first 10, after which - with the exception of a few spikes, well below the average "no-show" rates. 
This may suggest that repeat patients with long-term needs (e.g. chronic conditions) and high frequency of appointments have lower "no-show" rates. 
This reasoning is in line with the lower "no-show" rates of patients with diabetes and high blood pressure. These results are, however, preliminary and 
need further investigation.

### Appointment characteristics

- Hospital location (neighborhood)

34 out of the 81 hospitals have no-show rates higher than the average of 20%. It is important to look into the underlying factors for their 
higher-than-average no-show rates, so they can be addressed.

- SMS reminder

The differences are rather limited. It would be worthwhile to find more data on reminders to see why they have now had a bigger effect and how they can 
be made more effective.

- Length of time between the scheduling day and the appointment day

There is no clear pattern in the relationship between the no-show rates and the number of days between scheduling the appointment and its taking place. 
As expected, only the same-day appointments have significantly lower "no-show" rates.

### Limitations

This is an initial exploratory data analysis using descriptive statistics that is only the first step towards buliding a prediction model for patient "no-shows". The next steps would involve statistical modelling, for example using a regression model.

A more complete picture will emerge if the analysis includes data on type of appointment (e.g. general practitioner vs specialist), ethnicity and culture, and weather patterns which all may affect "no-show" rates. (Liu, D., Shin, WY., Sprecher, E. et al. Machine learning approaches to predicting no-shows in pediatric medical appointment. npj Digit. Med. 5, 50 (2022). https://doi.org/10.1038/s41746-022-00594-w)
