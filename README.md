# Data Description

The data on drug consumption records information about 1885 respondents, who are
primarily from English-speaking countries. 

For each respondent there are 12 attributes recorded in the original dataset: 
age, gender, level of education, country of residence and ethnicity, as well 
as personality information (measures of neuroticism, extraversion, openness to 
experience, agreeableness, conscientiousness, impulsivity, and sensation 
seeking). The personality variables are all numeric while the others listed are 
categorical. Furthermore, information is recorded for each participant on 
their use of 18 different drugs. These variables are categorical 
and have 6 levels: CL0 - never used, CL1 - used over a decade ago, CL2 - 
used in last decade,CL3 - used in last year, CL4 - used in last month, CL5 - 
used in last week, CL6 - used in last day. One of these variables is the 
recorded response of each participant to a question asking if they have taken 
a fictitious drug 'Semeron'. Participants who answered that they had taken 
this drug should be dropped from the data. The data contains no missing values. 

variables in the original dataset: age, gender, education, country, ethnicity, 
nscore, escore, oscore, ascore, cscore, impulsiveness, ss (sensation seeking), 
alcohol, amphet, amyl (amyl nitrate), benzos caff, cannabis, coke, crack, 
ecstasy, heroin, ketamine, legalh, lsd, meth, mushrooms, nicotine, 
VSA (volatile substance abuse)

For this project, we are only concerned about whether or not a respondent has 
taken any 'hard drugs' at least once in the past month. This is the list of 
drugs we are looking at: amphetamine, amyl nitrite, benzodiazepine, cocaine, 
crack cocaine, ecstasy, heroin, ketamine, legal highs, methamphetamine, 
and volatile substances. If a participant has used any of these drugs at
least once in the past month, then we classify him or her as 'Yes' under the 
'User' column, which in this case we use as our response variable. 
Otherwise, the participant is classified as 'No' under the  'User'
column. If a participant is classified with the value 'Yes', then we say he or
she is at risk of being a drug user. 

For our purposes we are only interested in twelve variables: User, Age, Gender, 
Education, Country, Ethnicity, Nscore, Escore, Oscore, Ascore, Cscore, and 
Impulsiveness.  We will later delve into these twelve variables in detail.
