# Can ASD be predicted given some behavioral and individual features?
## Introduction  
There are over 100,000 children in the UK that have been diagnosed with Autism Spectrum Disorder (ASD). Children on the ASD spectrum tend to show social interaction difficulties as well as speech and language problem.  Parents of children on ASD spectrum is faced with the challenge of dealing with the beahiour and also providing adequate support for the children to help them improve in the aspect of child development impacted by ASD.  
<br/>
Children with potential ASD shows some behavioral signs including avoiding eye contact, delayed speech, non-flexibility (getting really upset with change of routine), being obsessed with one toy, having trouble understanding other people’s feelings, struggling with jokes or sarcasm, repetitive behavior. This is not an exhaustive list of the signs of ASD in toddlers.
ASD diagnosis commences with parents of the child completing a Modified Checklist for Autism in Toddlers (M-CHAT). It is an early test for children between 16-30 months. However, this is not a proper diagnosis but could points to whether the child could develop ASD or not. Early detection of ASD is crucial as early intervention significantly improves the child’s condition. Children with ASD could get help from developmental pediatrician, occupational therapist, speech therapist and educational psychologist. It should be noted that confirmatory ASD diagnosis is usually delayed till a child is about 4-5 years. However, early prediction of the possibility of a child having ASD will significantly improve the child’s behavior, as appropriate support will be provided early.  
### Data Collection
The data for this project was obtained from kaggle website. There are two sets of data – Toddler autism data and Adult autism data  
Adult data:  
Number of records: 704  
Number of features: 20  
Features:  
A1_Score – A10_Score – set of behioural questions asked   
Age – Age of the participant in years  
Gender – Male or female  
Ethnicity – The ethnic group the participant belongs  
Had_jaundice – Whether the participant had jaundice at birth or not  
Family_History – Whether the participant has family history of autism  
Country of residence – Country where participant resides  
Used_app_before – Whether the participant has used the app before  
Result – The overall result of the test based on A1_Score – A10_Score  
Age_desc – Age description of participant ( e.g 18 years and above)  
Relation – Relationship of the test taker with the person answering the questionnaire  
Class – Target class (whether the participant has autism or not)  
<br/>  
Toddler data:  
Number of records: 1054  
Number of features: 18  
Features:  
A1 – A10 - Set of behioural questions asked  
Age – The child’s age in Months  
Sex – Male or female  
Ethnicity – The ethnic group the participant belongs  
Had_jaundice – Whether the child developed jaundice at birth or not  
Family_History – Whether the child has a family member with autism  
Qchat-10-Score - The overall result of the test based on A1 – A10 scores  
Test_taker_relation - Relationship of the test taker with the person answering the questionnaire  
Class – Target class  


