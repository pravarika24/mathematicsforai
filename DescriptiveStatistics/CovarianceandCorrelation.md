Covariance and correlation are two statistical measures used to determine the relationship between two variables. Both are used to understand how changes in one variable are associated with changes in another variable

Covariance: Covariance is a measure of how much random variable schange together. If the variable tend to increase and dcrease together, the covariance is positive. If one tends to increase when other decreases, the covariance is negative

X = 2,4,6,8
Y = 3,5,7,9 

[Qauntify the relationship between X and Y]

X increases Y increases(positive covariance)
X decreases Y decreases(Negative covariance)
X increases Y decreases(Negative covariance)
X decreases Y decreases(positive covariance)

size of house     price of size
1200 sqft           45 lakhs
1300 sqft           50 lakhs
1500 sqft           75 lakhs

if size of house increases, price of house increases

covariance(x,y) = sigma(x-x(bar))(y-y(bar))/n-1

cov(x,x) = sigma(x-x(bar))(x-x(bar))/n-1

cov(x,x) = var(x)
x = datapoint of random variable x
x(bar) = sample mean of x
y = data point of random variable y
y(bar) = sample mean of y

Example: 
Students 
hourse studied      ExamScore
2                       50
3                       60
4                       70
5                       80
6                       90

x(bar) = 2+3+4+5+6/5 = 4
y(bar) = 50+60+70+80+90/5 = 70

covariance = (2-4)(50-70)+(3-4)(60-70)+(4-4)(70-70)+(5-4)(80-70)+(6-4)(90-70)/5-1 = 20

positive covariance - indicates the number of studies increases the exam score

Advantages of covariance 
1) Quantify the relationship between x and y 

Disadvantages of covariance
1) Covariance does not have specific limitation - negative infinity to positive infinity

Correlation - 
1) Pearson correlation coefficient - [-1 to 1] - it limits the values from -1 to +1

The more the value towards +1 the more +ve correlated x and y 

The more the value towards -1 the more -ve correlated it is (x,y)
2) Spearman Rank Correlation 
Pearson correlation is not able to capture correlation for non linear data

Thos issue is solved spearman rank correlation

x       y   rank(x)  rank(y)
1       2     2.       1
3       4      3        2
5       6      4        3
7       8.     5        5
0       7       1       4

Real world Examples:
Feature selection

size of house(increase)   numberofrooms(increase)    location(increase) price(increase)



