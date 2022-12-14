**Author**: Kun Zhang, Wei Fan, XiaoJing Yuan

**Source**: [UCI](https://archive.ics.uci.edu/ml/datasets/ozone+level+detection)

**Please cite**:   

Forecasting skewed biased stochastic ozone days: analyses, solutions and beyond, Knowledge and Information Systems, Vol. 14, No. 3, 2008. 


1 . Abstract: 
Two ground ozone level data sets are included in this collection. One is the eight hour peak set (eighthr.data), the other is the one hour peak set (onehr.data). Those data were collected from 1998 to 2004 at the Houston, Galveston and Brazoria area.

2. Source:

Kun Zhang, zhang.kun05 '@' gmail.com, Department of Computer Science, Xavier University of Lousiana 
Wei Fan, wei.fan '@' gmail.com, IBM T.J.Watson Research 
XiaoJing Yuan, xyuan '@' uh.edu, Engineering Technology Department, College of Technology, University of Houston 


3. Data Set Information:

All the attribute start with T means the temperature measured at different time throughout the day; and those starts with WS indicate the wind speed at various time. 

WSR_PK: continuous. peek wind speed -- resultant (meaning average of wind vector) 
WSR_AV: continuous. average wind speed 
T_PK: continuous. Peak T 
T_AV: continuous. Average T 
T85: continuous. T at 850 hpa level (or about 1500 m height) 
RH85: continuous. Relative Humidity at 850 hpa 
U85: continuous. (U wind - east-west direction wind at 850 hpa) 
V85: continuous. V wind - N-S direction wind at 850 
HT85: continuous. Geopotential height at 850 hpa, it is about the same as height at low altitude 
T70: continuous. T at 700 hpa level (roughly 3100 m height) 

RH70: continuous. 
U70: continuous. 
V70: continuous. 
HT70: continuous. 

T50: continuous. T at 500 hpa level (roughly at 5500 m height) 

RH50: continuous. 
U50: continuous. 
V50: continuous. 
HT50: continuous. 

KI: continuous. K-Index [Web Link] 
TT: continuous. T-Totals [Web Link] 
SLP: continuous. Sea level pressure 
SLP_: continuous. SLP change from previous day 

Precp: continuous. -- precipitation


4. Attribute Information:

The following are specifications for several most important attributes that are highly valued by Texas Commission on Environmental Quality (TCEQ). More details can be found in the two relevant papers. 

O 3 - Local ozone peak prediction 
Upwind - Upwind ozone background level 
EmFactor - Precursor emissions related factor 
Tmax - Maximum temperature in degrees F 
Tb - Base temperature where net ozone production begins (50 F) 
SRd - Solar radiation total for the day 
WSa - Wind speed near sunrise (using 09-12 UTC forecast mode) 
WSp - Wind speed mid-day (using 15-21 UTC forecast mode) 


5. Relevant Papers:

Forecasting skewed biased stochastic ozone days: analyses, solutions and beyond, Knowledge and Information Systems, Vol. 14, No. 3, 2008. 

It Discusses details about the dataset, its use as well as various experiments (both cross-validation and streaming) using many state-of-the-art methods. 
A shorter version of the paper (does not contain some detailed experiments as the journal paper above) is in: 
Forecasting Skewed Biased Stochastic Ozone Days: Analyses and Solutions. ICDM 2006: 753-764

Downloaded from openml.org.