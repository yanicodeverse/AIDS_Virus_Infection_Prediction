# Acquired Immunodeficiency Syndrome (AIDS)

- AIDS (Acquired Immunodeficiency Syndrome) is a disease caused by the HIV (Human Immunodeficiency Virus). This virus weakens the immune system, making the body vulnerable to infections.

- HIV spreads through infected blood, semen, vaginal fluids, and breast milk. It can be transmitted via unprotected sexual contact, sharing infected needles, or from an infected mother to her baby during childbirth or breastfeeding.

- In the early stages, HIV may not show noticeable symptoms. However, over time, it weakens the immune system, leading to symptoms like fatigue, weight loss, fever, and frequent infections.

- There is no permanent cure for AIDS, but Antiretroviral Therapy (ART) helps control HIV and slow its progression. Prevention includes practicing safe sex, using clean needles, and regular HIV testing.

# About Dataset

*The AIDS_Classification_50000.csv dataset is a comprehensive resource specifically compiled for researchers and healthcare professionals focusing on the statistical analysis of AIDS (Acquired Immunodeficiency Syndrome). Composed of 50,000 instances, this dataset encapsulates a broad spectrum of clinical and demographic variables related to AIDS patients. Each record in the dataset holds data across 23 columns, indicating various patient attributes including treatment details, demographic information, clinical test results, and disease progression indicators.*

# Data Description:

- time: Time since the baseline measurement, in days.
- trt: Treatment code (0, 1, 2), where each number signifies a different treatment regimen.
- age: Age of the patient in years. {in the range of [12,68]}
- wtkg: Weight of the patient in kilograms. {in the range of [42, 149]}
- hemo: Presence of Hemophilia (0 = No, 1 = Yes).
- homo: Homosexual behavior (0 = No, 1 = Yes).
- drugs: Drug use (0 = No, 1 = Yes).
- karnof: Karnofsky score indicating patient's functional impairment (scores range from 0 to 100). {min_val, max_val = 76, 100}
- oprior: Number of opportunistic infections prior to study.
- z30: Presence of Z30 gene (0 = No, 1 = Yes).
- preanti: Months before receiving antiretroviral therapy.
- race: Race (0 = Non-white, 1 = White).
- gender: Gender (0 = Female, 1 = Male).
- str2: Stratification variable 2.
- strat: Overall stratification.
- symptom: Presence of specific AIDS-related symptoms (0 = No, 1 = Yes).
- treat: Treatment response (0 = No, 1 = Yes).
- offtrt: Off treatment (0 = No, 1 = Yes).
- cd40: CD4 count at the baseline. {in the range [236, 930]}
- cd420: CD4 count at 20 weeks. {in the range [327, 1119]}
- cd80: CD4 count at 8 weeks. {in the range [885, 4656]}
- cd820: CD4 count at 20 weeks post the 8-week measurement. {in the range [649, 3585]}
- infected: HIV infection status (0 = Negative, 1 = Positive).
