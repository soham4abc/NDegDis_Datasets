# About Dataset
## Context
The HandPD dataset is composed of handwritten exams from two groups of individuals: <br/>
- (i) Healthy Group and 
- (ii) Patient Group, being the latter one composed of individuals affected by Parkinson's Disease (PD).

## Content
The dataset contains 92 individuals, divided into 18 healthy people (CHealthy Group) and 74 patients (Patients Group). Follows, below, a brief description of each group:

- Healthy Group: 6 male and 12 female individuals with ages ranging from 19 to 79 years old (average age of 44.22±16.53 years). Among those individuals, 2 are left-handed and 16 are right-handed.
- Patient Group: 59 male and 15 female individuals with ages ranging from 38 to 78 years old (average age of 58.75±7.51 years). Among those individuals, 5 are left-handed and 69 are right-handed.

Therefore, the entire dataset is composed of 736 images labeled in two groups: the healthy group containing 72 images, and the patient group containing 296 images, having a dataset with 368 images from each drawing, i.e. spirals and meanders. The images are labeled as follows: ID_EXAM-ID_IMAGE.jpg, in which ID_EXAM stands for the exam's identifier, and ID_IMAGE denotes the number of the image of that exam. Notice we may have more than one ID_EXAM for the same individual since some of them have filled out four images by form. The Spiral_HandPD dataset (images) can be downloaded [here](http://www2.fc.unesp.br/~papa/pub/datasets/Handpd/Spiral_HandPD.zip) and Meander_HandPD images can be downloaded [here](http://www2.fc.unesp.br/~papa/pub/datasets/Handpd/Meander_HandPD.zip)

The aforementioned file is organized in columns, as follows:

- ID_EXAM: identifier of the exam (handwritten form)
- IMAGE_NAME: name of the image
- ID_PATIENT: identifier of the patient
- CLASS_TYPE: 1 = control group and 2 = patient group
- GENDER: M = male and F = female
- RIGH/LEFT-HANDED: R = right handed and L = left handed
- AGE: age (years)
- RMS: root mean square (Equation 3 of the paper)
- MAX_BETWEEN_ET_HT: the maximum difference between ET (exam template) and HT (handwritten trace) radius (Equation 4 of the paper)
- MIN_BETWEEN_ET_HT: the maximum difference between ET and HT radius (Equation 5 of the paper)
- STD_DEVIATION_ET_HT: standard deviation of the difference between ET and HT radius
- MRT: mean relative tremor
- MAX_HT: maximum HT radius
- MIN_HT: minimum HT radius
- STD_HT: standard deviation of HT radius
- CHANGES_FROM_NEGATIVE_TO_POSITIVE_BETWEEN_ET_HT: the number of times the difference between ET and HT radius changes from negative to positive, or vice-versa.

## Acknowledgements
For more information about HandPD dataset, please feel free to keep in touch with Clayton (clayton.pereira AT gmail DOT com) or João Paulo (papa.joaopaulo AT gmail DOT com).

## Source
https://www.kaggle.com/datasets/claytonteybauru/spiral-handpd