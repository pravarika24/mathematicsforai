Analysis of Variance (ANOVA)
Hypothesis Testing in ANOVA(Partioining Of Variance In the ANOVA)

Null hypothesis H0 = mu1 = mu2 = mu3_______muk
Alternate hypothesis + atleast one of the sample mean is not equal 

Test statistics

F = Variance between samples/Variance within sample

x1 = 1 2 4 5 3  mean = 3 variance between samples = 
x2 = 6 7 3 2 1. mean = 19/5
x3 = 5 6 3 2 4  mean = 4

One way ANOVA

One factor with atleast 2 levels, levels are independdent 

Doctors want to test a new medication which reduces headaches. they splits the into 3 conditions[15mg, 30 mg,45 mg] later on the doctor ask the patient to rate the headache between [1-10]. Are there any differences between 3 conditions alpa = 0.05

15mg = 9 8 7 8 8 9 8 
30mg = 7 6 6 7 8 7 6 
45mg = 4 3 2 3 4 3 2 

1) define null and alternate hypothesis 
mean of 15 mg = mean of 30 mg = mean of 45 mg

alternative hypothesis = atleast one of mean is not equal 

2) Calculate degree of freedom

N= 21 n=7 a =3(categories)

df between = a-1 = 3-1 = 2 range of values (2,18) - f table alpha = 0.05 to find critical value
df within = N-a =21-3 =18
df total = N-1 = 20

3) Decision Boundary

crticial value from f table = 3.556

If F is greater than 3.556 then we reject null hypothesis


F = variance between samples/variance with sample

sum of sqaure 
between 
within
total

df
between 2
within 18
total.  20

ms
between 
within 
total

f
between 
within 
total


for 15 mg = 9+8_7+8+8+9+8 = 57
for 30 mg = 47
45mg= 21

57**2+47**2+21**2/7 - 57**2+47**2+21**2/21
=98.67

within samples = 9**2+8**2_________ = 853 -57**2+47**2+21**2

ss/df = ms

f = ms btween/ms within = 86.56 is greater than 3.556 then we reject the null hypothesis



