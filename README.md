## Fitness-Data-Pearson-Correlation-Analysis
Finding and describing relationships between variables:

Various measures of heart and pulse rate were taken on men in a physical fitness course at N.C. State University:

runpulse: Pulse rate while running

maxpulse: Maximum pulse rate

rstpulse: Resting pulse rate

oxy: oxygen consumption


In this exercise, Scatter plots and correlations are generated for the variables and the results are interpreted. The limitations of correlation coefficient for the Fitness data are also checked;

The data used is as follows:


44 89.47 44.609 11.37 62 178 182

40 75.07 45.313 10.07 62 185 185

44 85.84 54.297 8.65 45 156 168

42 68.15 59.571 8.17 40 166 172

38 89.02 49.874 9.22 55 178 180

47 77.45 44.811 11.63 58 176 176

40 75.98 45.681 11.95 70 176 180

43 81.19 49.091 10.85 64 162 170

44 81.42 39.442 13.08 63 174 176

38 81.87 60.055 8.63 48 170 186

44 73.03 50.541 10.13 45 168 168

45 87.66 37.388 14.03 56 186 192

45 66.45 44.754 11.12 51 176 176

47 79.15 47.273 10.60 47 162 164

54 83.12 51.855 10.33 50 166 170

49 81.42 49.156 8.95 44 180 185

51 69.63 40.836 10.95 57 168 172

51 77.91 46.672 10.00 48 162 168

48 91.63 46.774 10.25 48 162 164

49 73.37 50.388 10.08 67 168 168

57 73.37 39.407 12.63 58 174 176

54 79.38 46.080 11.17 62 156 165

52 76.32 45.441 9.63 48 164 166

50 70.87 54.625 8.92 48 146 155

51 67.25 45.118 11.08 48 172 172

54 91.63 39.203 12.88 44 168 172

51 73.71 45.790 10.47 59 186 188

57 59.08 50.545 9.93 49 148 155

49 76.32 48.673 9.40 56 186 188

48 61.24 47.920 11.50 52 170 176

52 82.78 47.467 10.50 53 170 172


### Findings and conclusions

1. Variable Age is only associated with Maxpulse since p<5% and r=-0.43, which is considered weak correlation

2. Variable Weight is not associated with any other variable

3. Variable Oxy is associated with runtime, rstpulse and runpulse (p<5%). R is negative, which indicates and inverse correlation. R is strong for Runtime at 0.86, and weak for the other two variables at 0.40 for both

4. Variable Runtime is associated with rstpulse (p,5%). R is positive but weak at 0.45

5. Var Runpulse is associated with Maxpulse (p<5%). R is positive and strong at 0.93

6. The scatter plots shown in the "Results" filealso verify these findings and the associated listed below. The scatterplots show us linearity for all and also the strenght of the relationship (dispersion).




### Checking the limitations of the correlation coefficient for the Fitness data

#### For scatterplots A,B,C,D,E in the above scatterplot matrix – CONDITIONS NOT MET

1.Level of measurement: Both variables are continuous, so this condition is met

2.Related pairs: Each observation have a pair of values, so this condition is met (from printed dataset)

3.Absence of outliers: From the plots and data table, this condition is met

4.Linearity: The observations do not form a linear pattern


#### For scatterplots F in the above scatterplot matrix - CONDITIONS MET

1.Level of measurement: Both variables are continuous, so this condition is met

2.Related pairs: Each observation have a pair of values, so this condition is met (from printed dataset)

3.Absence of outliers: From the plots and data table, this condition is met

4.Linearity: The observations DO form a linear pattern. The observations tend to DECREASE withthe increase of Age and Maxpulse


#### For scatterplots G,H,I,J,K in the above scatterplot matrix – CONDITIONS NOT MET

1.Level of measurement: Both variables are continuous, so this condition is met

2.Related pairs: Each observation have a pair of values, so this condition is met (from printed dataset)

3.Absence of outliers: From the plots and data table, this condition is met

4.Linearity: The observations do not form a linear pattern


#### For scatterplots L,M,N in the above scatterplot matrix - CONDITIONS MET

1.Level of measurement: Both variables are continuous, so this condition is met

2.Related pairs: Each observation have a pair of values, so this condition is met (from printed obs)

3.Absence of outliers: From the plots and data table, this condition is met (HOWEVER, I WOULD LIKE TO TRY REMOVING THE POINTS HIGHLIGHTED IN SCATTERPLOTS M AND N AS THEY APPEAR TO BEOUTLIERS – MORE STUDY OF QUARTILES IS NECESSARY TO DEFINE OUTLIERS IN THE DATA FOR THESE VARIABLES)

4.Linearity: The observations DO form a linear pattern. The observations tend to DECREASE withthe increase of Oxy and Runtime, Oxy and RstPulse , Oxy and Runpulse respectively.


#### For scatterplots O in the above scatterplot matrix – CONDITIONS NOT MET

1.Level of measurement: Both variables are continuous, so this condition is met

2.Related pairs: Each observation have a pair of values, so this condition is met (from printed dataset)

3.Absence of outliers: From the plots and data table, this condition is met

4.Linearity: The observations do not form a linear pattern


#### For scatterplots P in the above scatterplot matrix - CONDITIONS MET

1.Level of measurement: Both variables are continuous, so this condition is met

2.Related pairs: Each observation have a pair of values, so this condition is met (from printed dataset)

3.Absence of outliers: From the plots and data table, this condition is met

4.Linearity: The observations DO form a linear pattern. The observations tend to INCREASE withthe increase of runtime and rstpulse


#### For scatterplots Q,R in the above scatterplot matrix – CONDITIONS NOT MET

1.Level of measurement: Both variables are continuous, so this condition is met

2.Related pairs: Each observation have a pair of values, so this condition is met (from printed dataset)

3.Absence of outliers: From the plots and data table, this condition is met

4.Linearity: The observations do not form a linear pattern


#### For scatterplots S,T in the above scatterplot matrix – CONDITIONS NOT MET

1.Level of measurement: Both variables are continuous, so this condition is met

2.Related pairs: Each observation have a pair of values, so this condition is met (from printed dataset)

3.Absence of outliers: From the plots and data table, this condition is met

4.Linearity: The observations do not form a linear pattern


#### For scatterplots U in the above scatterplot matrix - CONDITIONS MET

1.Level of measurement: Both variables are continuous, so this condition is met

2.Related pairs: Each observation have a pair of values, so this condition is met (from printed dataset)

3.Absence of outliers: From the plots and data table, this condition is met

4.Linearity: The observations DO form a linear pattern. The observations tend to INCREASE withthe increase of runpulse and maxpulse
