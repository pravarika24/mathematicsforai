Binomial Distribution

In probability theory and statistics the binomial distribution with parameters n and p is the discrete probability distribution of the numbers of successes in s sequence of n independent experiments, each asking a yes-no question, and each with its own Boolean - valued outcome: sucess(with probability p ) or failure(with probability q = 1-p). A single success/failure experiment is also called bernoulli trial or bernoulli experiment ans sequence of outcomes is called bernoulli process, for a single trial n=1, the binomial distribution is bernoulli distribution. The binomial distribution is the basis for the popular binomial test pf statistical significance

1) Discrete Random variable
2) every outcome of the experiment is binary
3) These experiments are performed for n trials
Ex: Tossing a coin 10 times, n=10

Notation: B(n,p)

parameters: ne{0,1,3,4......} = no of trails or experiment

p {0,1} = success probability for each trial

q = 1-p

support = ke {0,1,2,3,...n} - number of success

P(k,n,p) = nck p**k(i-p)**n-k

mean = n*p

variance = npq

standard deviation = squareroot of npq

Number of trial(n) = 5
Probability of success(p) = 0.5
no of success(k) = varies from 0 to 5

What is the probability of getting exactly 3 heads in 5 flips

n= 5 k =3

p(x=3) = 5c3(0.5)*3 *(1-0.5)5-3

= 0.3125

Ex: Quality Control

Scenario: Inspecting 10 items in a factory where each item has a 10% chance of being defective
no of trails = 10 
probability of sucess = 0.1(defective)
no of sucess varies from 0 to 10

What is the probability of finding exactly two defective items in a sample of 10?

P(x=2) = 10c2 0.1**2 (1-0.1) = 0.1937






