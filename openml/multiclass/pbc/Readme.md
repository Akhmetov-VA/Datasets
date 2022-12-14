**Author**:   
**Source**: Unknown -   
**Please cite**:   

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

 Case number deleted. X treated as the class attribute.

 As used by Kilpatrick, D. & Cameron-Jones, M. (1998). Numeric prediction
 using instance-based learning with encoding length selection. In Progress
 in Connectionist-Based Information Systems. Singapore: Springer-Verlag.

 !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

 NAME:  PBC Data
 SIZE:  418 observations, 20 variables
 
 
 
 DESCRIPTIVE ABSTRACT:
 
 Below is a description of the variables recorded from the Mayo Clinic trial 
 in primary biliary cirrhosis (PBC) of the liver conducted between 1974 and 
 1984.  A total of 424 PBC patients, referred to Mayo Clinic during
 that ten-year interval, met eligibility criteria for the randomized placebo 
 controlled trial of the drug D-penicillamine. The first 312 cases in the data 
 set participated in the randomized trial, and contain largely complete data. 
 The additional 112 cases did not participate in the clinical trial, but 
 consented to have basic measurements recorded and to be followed for survival.
 Six of those cases were lost to follow-up shortly after diagnosis, so there 
 are data here on an additional 106 cases as well as the 312 randomized 
 participants. Missing data items are denoted by ".".  At least one space 
 separates each variable in the .DAT file.  Censoring was due to liver 
 transplantation for twenty-five subjects with the following case numbers: 
 5, 105, 111, 120, 125, 158, 183, 241, 246, 247, 254, 263, 264, 265, 274, 
 288, 291, 295, 297, 345, 361, 362, 375, 380, 383.
 
 
 
 SOURCE:  Counting Processes and Survival Analysis by T. Fleming & 
          D. Harrington, (1991),  published by John Wiley & Sons.
 
 
 
 VARIABLE DESCRIPTIONS:
 
 The data are in free format.  That is, at least one blank space separates
 each variable.  The variables contained in the .DAT are:
 
 
 N:   Case number.
 X:   The number of days between registration and the earlier of
      death, liver transplantation, or study analysis time in July, 1986.
 D:   1 if X is time to death, 0 if time to censoring
 Z1:  Treatment Code, 1 = D-penicillamine, 2 = placebo.
 Z2:  Age in years. For the first 312 cases, age was calculated by
      dividing the number of days between birth and study registration by 365.
 Z3:  Sex, 0 = male, 1 = female.
 Z4:  Presence of ascites, 0 = no, 1 = yes.
 Z5:  Presence of hepatomegaly, 0 = no, 1 = yes.
 Z6:  Presence of spiders 0 = no, 1 = Yes.
 Z7:  Presence of edema, 0 = no edema and no diuretic therapy for
      edema; 0.5 = edema present for which no diuretic therapy was given, or 
      edema resolved with diuretic therapy; 1 = edema despite diuretic therapy
 Z8:  Serum bilirubin, in mg/dl.
 Z9:  Serum cholesterol, in mg/dl.
 Z10: Albumin, in gm/dl.
 Z11: Urine copper, in mg/day.
 Z12: Alkaline phosphatase, in U/liter.
 Z13: SGOT, in U/ml.
 Z14: Triglycerides, in mg/dl.
 Z15: Platelet count; coded value is number of platelets
      per-cubic-milliliter of blood divided by 1000.
 Z16: Prothrombin time, in seconds.
 Z17: Histologic stage of disease, graded 1, 2, 3, or 4.
 
 
 
 
 STORY BEHIND THE DATA:
 
 Between January, 1974 and May, 1984, the Mayo Clinic conducted a
 double-blinded randomized trial in primary biliary cirrhosis of the liver
 (PBC), comparing the drug D-penicillamine (DPCA) with a placebo. There
 were 424 patients who met the eligibility criteria seen at the Clinic while
 the trial was open for patient registration. Both the treating physician and
 the patient agreed to participate in the randomized trial in 312 of the 424
 cases. The date of randomization and a large number of clinical, biochemical,
 serologic, and histologic parameters were recorded for each of the 312
 clinical trial patients. The data from the trial were analyzed in 1986 for
 presentation in the clinical literature. For that analysis, disease and 
 survival status as of July, 1986, were recorded for as many patients as 
 possible.  By that date, 125 of the 312 patients had died, with only 11 
 not attributable to PBC.  Eight patients had been lost to follow up, and 19 
 had undergone liver transplantation. 
 
 PBC is a rare but fatal chronic liver disease of unknown cause,
 with a prevalence of about 50-cases-per-million population. The primary
 pathologic event appears to be the destruction of interlobular bile ducts,
 which may be mediated by immunologic mechanisms. The data discussed here are
 important in two respects. First, controlled clinical trials are difficult to
 complete in rare diseases, and this case series of patients uniformly
 diagnosed, treated, and followed is the largest existing for PBC. The
 treatment comparison in this trial is more precise than in similar trials
 having fewer participants and avoids the bias that may arise in comparing
 a case series to historical controls. Second, the data present an
 opportunity to study the natural history of the disease. We will see that, 
 despite the immunosuppressive properties of DPCA, there are no detectable
 differences between the distributions of survival times for the DPCA and
 placebo treatment groups. This suggests that these groups can be combined
 in studying the association between survival time from randomization and
 clinical and other measurements. In the early to mid 1980s, the rate of 
 successful liver transplant increased substantially, and transplant has 
 become an effective therapy for PBC. The Mayo Clinic data set is therefore 
 one of the last allowing a study of the natural history of PBC in patients 
 who were treated with only supportive care or its equivalent. The PBC data 
 can be used to: estimate a survival distribution; test for differences 
 between two groups; and estimate covariate effects via a regression
 model.

Downloaded from openml.org.