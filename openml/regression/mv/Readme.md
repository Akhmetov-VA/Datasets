**Author**: Luis Torgo  
**Source**: [original](http://www.dcc.fc.up.pt/~ltorgo/Regression/DataSets.html) -   
**Please cite**:   

This is an artificial data set with dependencies between the attribute values. The cases are generated using the following method:

X1 : uniformly distributed over [-5,5]
X2 : uniformly distributed over [-15,-10]
X3 : IF (X1 > 0) THEN X3 = green
 ELSE X3 = red with probability 0.4 and X4=brown with prob. 0.6
X4 : IF (X3=green) THEN X4=X1+2X2
 ELSE X4=X1/2 with prob. 0.3, and X4=X2/2 with prob. 0.7
X5 : uniformly distributed over [-1,1]
X6 : X6=X4*[epsilon], where [epsilon] is uniformly distribute over [0,5]
X7 : X7=yes with prob. 0.3 and X7=no with prob. 0.7
X8 : IF (X5 < 0.5) THEN X8 = normal ELSE X8 = large
X9 : uniformly distributed over [100,500]
X10 : uniformly distributed integer over the interval [1000,1200]
 
Obtain the value of the target variable Y using the rules:
IF (X2 > 2 ) THEN Y = 35 - 0.5 X4
 ELSE IF (-2 <= X4 <= 2) THEN Y = 10 - 2 X1
 ELSE IF (X7 = yes) THEN Y = 3 -X1/X4
 ELSE IF (X8 = normal) THEN Y = X6 + X1
 ELSE Y = X1/2

Source: collection of regression datasets by Luis Torgo (ltorgo@ncc.up.pt) at http://www.dcc.fc.up.pt/~ltorgo/Regression/DataSets.html

Downloaded from openml.org.