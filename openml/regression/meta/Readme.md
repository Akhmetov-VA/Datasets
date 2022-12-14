**Author**:   
**Source**: Unknown - Date unknown  
**Please cite**:   

1. Title: meta-data

2. Sources:
(a) Creator:
LIACC - University of Porto
R.Campo Alegre 823
4150 PORTO
(b) Donor: P.B.Brazdil or J.Gama            Tel.:  +351 600 1672
LIACC, University of Porto               Fax.:  +351 600 3654
Rua Campo Alegre 823                     Email:  statlog-adm@ncc.up.pt
4150 Porto, Portugal
(c) Date: March, 1996

(d) Acknowlegements:
LIACC wishes to thank Commission of European Communities
for their support. Also, we wish to thank the following partners
for providing the individual test results:

- Dept. of Statistics, University of Strathclyde, Glasgow, UK
- Dept. of Statistics, University of Leeds, UK
- Aston University, Birmingham, UK
- Forschungszentrum Ulm, Daimler-Benz AG, Germany
- Brainware GmbH, Berlin, Germany
- Frauenhofer Gesellschaft IITB-EPO, Berlin, Germany
- Institut fuer Kybernetik, Bochum, Germany
- ISoft, Gif sur Yvette, France
- Dept. of CS and AI, University of Granada, Spain


3. Past Usage:


Meta-Data was used in order to give advice about which classification
method is appropriate for a particular dataset.
This work is described in:

-"Machine Learning, Neural and Statistical Learning"
Eds. D.Michie,D.J.Spiegelhalter and C.Taylor
Ellis Horwood-1994

- "Characterizing the Applicability of
Classification Algorithms Using Meta-Level Learning",
P. Brazdil, J.Gama and B.Henery:
in Proc. of Machine Learning - ECML-94,
ed. F.Bergadano and L.de Raedt,LNAI Vol.784 Springer-Verlag.

-"Characterization of Classification Algorithms"
J.Gama, P.Brazdil
in Proc. of EPIA 95, LNAI Vol.990
Springer-Verlag, 1995


4. Relevant Information:n
This DataSet is about the results of Statlog project.
The project performed a comparative study between Statistical, Neural
and Symbolic learning algorithms.

Project StatLog (Esprit Project 5170) was concerned with comparative
studies of different machine learning, neural and statistical
classification algorithms. About 20 different algorithms were
evaluated on more than 20 different datasets. The tests carried out
under project produced many interesting results.

Algorithms                      DataSets
-------------------------       --------------------------
C4.5            NewId           Credit_Austr    Belgian
AC2             CART            Chromosome      Credit_Man
IndCART         Cal5            CUT             DNA
CN2             ITRule          Diabetes        Digits44
Discrim         QuaDisc         Credit_German   Faults
LogDisc         ALLOC80         Head            Heart
kNN             SMART           KLDigits        Letters
BayesTree       CASTLE          New_Belgian     Sat_Image
DIPLO92         RBF             Segment         Shuttle
LVQ             Backprop        Technical       TseTse
Kohonen                         Vehicle


The results of these tests are comprehensively described in a book
(D.Michie et.al, 1994).

5. Number of Instances: 528

6. Number of Attributes: 22 (including an Id#) plus the class attribute
-- all but two attributes are continuously valued

7. Attribute Information:
1.   DS_Name         categorical     Name of DataSet
2.   T               continuous      Number of examples in test set
3.   N               continuous      Number of examples
4.   p               continuous      Number of attributes
5.   k               continuous      Number of classes
6.   Bin             continuous      Number of binary Attributes
7.   Cost            continuous      Cost (1=yes,0=no)
8.   SDratio         continuous      Standard deviation ratio
9.   correl          continuous      Mean correlation between attributes
10.   cancor1         continuous      First canonical correlation
11.   cancor2         continuous      Second canonical correlation
12.   fract1          continuous      First eigenvalue
13.   fract2          continuous      Second eigenvalue
14.   skewness        continuous      Mean of |E(X-Mean)|^3/STD^3
15.   kurtosis        continuous      Mean of |E(X-Mean)|^4/STD^4
16.   Hc              continuous      Mean entropy of attributes
17.   Hx              continuous      Entropy of classes
18.   MCx             continuous      Mean mutual entropy of class and attributes
19.   EnAtr           continuous      Equivalent number of attributes
20.   NSRatio         continuous      Noise-signal ratio
21.   Alg_Name        categorical     Name of Algorithm
22.   Norm_error      continuous      Normalized Error (continuous class)


8. Missing Attribute Values:

Note that fract2 and cancor2 only apply to datasets with more than
2 classes. When they appear as '?' this means a don't care value.

Summary Statistics:

Attribute       Min     Max     Mean    Std
T               270     20000   4569.05 5704.01
N               270     58000   10734.2 14568.8
p               6       180     29.5455 36.8533
k               2       91      9.72727 19.3568
Bin             0       43      3.18182 9.29227
Cost            0       1       0.13636 0.35125
SdRatio         1.0273  4.0014  1.4791  0.65827
Correl          0.0456  0.751   0.23684 0.1861
Cancor1         0.5044  0.9884  0.79484 0.15639
Cancor2         0.1057  0.9623  0.74106 0.269
Fract1          0.1505  1       0.70067 0.3454
Fract2          0.2807  1       0.70004 0.29405
Skewness        0.1802  6.7156  1.78422 1.79022
Kurtosis        0.9866  160.311 22.6672 41.8496
Hc              0.2893  4.8787  1.87158 1.44665
Hx              0.3672  6.5452  3.34502 1.80383
Mcx             0.0187  1.3149  0.31681 0.33548
EnAtr           1.56006 160.644 20.6641 35.6614
NsRatio         1.02314 159.644 28.873  37.925

Downloaded from openml.org.