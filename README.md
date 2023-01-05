# Data-science-stats


Gender (Male or Female)	Discrete
Q1) Identify the Data type for the Following:

Q2) Identify the Data types, which were among the following
Nominal, Ordinal, Interval, Ratio.
Data	Data Type
Gender	Discrete-Nominal
High School Class Ranking	Discrete-Ordinal
Celsius Temperature	Continuous-Ratio
Weight	Continuous-
Hair Color	Discrete-Ratio
Socioeconomic Status	Discrete-Ordinal
Fahrenheit Temperature	Continuous-Ratio
Height	Continuous-Ratio
Type of living accommodation	Discrete-ordinal
Level of Agreement	Discrete-Interval
IQ(Intelligence Scale)	Discrete-Interval
Sales Figures	Discrete-Interval
Blood Group	Discrete-Ratio
Time Of Day	Continuous-Interval
Time on a Clock with Hands	Continuous-Interval
Number of Children	Discrete-Ratio
Religious Preference	Discrete-Ordinal
Barometer Pressure	Continuous-Ratio
SAT Scores	Discrete-Ratio
Years of Education	Discrete-Nominal


Q3) Three Coins are tossed, find the probability that two heads and one tail are obtained?
Sol:  P(H H T) + P(H T H)+ P(T H H)
=1/8+1/8+1/8
=3/8

Q4)  Two Dice are rolled, find the probability that sum is
a)	Equal to 1
b)	Less than or equal to 4
c)	Sum is divisible by 2 and  3
Sol:
a)	There is no corresponds to Sum is equal to 1 i.e. 0/36

b)	(1,1) (1,2) (2,1),(1,3) (2,2) (3,1) = 6 outcomes i.e.6/36

c)	 (1,5) (2,4) (3,3) (4,2) ( (5,1)  (6,6)
 i.e.6/36

Q5)  A bag contains 2 red, 3 green and 2 blue balls. Two balls are drawn at random. What is the probability that none of the balls drawn is blue?
Sol:
P (2R,3G,2B) P(5/7,4/6)
=20/42
=10/21



Q6) Calculate the Expected number of candies for a randomly selected child 
Below are the probabilities of count of candies for children (ignoring the nature of the child-Generalized view)
CHILD	Candies count	Probability
A	1	0.015
B	4	0.20
C	3	0.65
D	5	0.005
E	6	0.01
F	2	0.120
Child A – probability of having 1 candy = 0.015.
Child B – probability of having 4 candies = 0.20
Sol:
Total Count of Candies=1*0,015+4*0.20+3*0.65+5*0.005+6*0.01+2*0.120
=3.09



Q7) Calculate Mean, Median, Mode, Variance, Standard Deviation, Range &     comment about the values / draw inferences, for the given dataset
-	For Points,Score,Weigh>
Find Mean, Median, Mode, Variance, Standard Deviation, and Range and also Comment about the values/ Draw some inferences.
Sol: 
  



Q8) Calculate Expected Value for the problem below
a)	The weights (X) of patients at a clinic (in pounds), are
108, 110, 123, 134, 135, 145, 167, 187, 199
Assume one of the patients is chosen at random. What is the Expected Value of the Weight of that patient?
Sol:


Mean=145.33



Q9) Calculate Skewness, Kurtosis & draw inferences on the following data
      Cars speed and distance 
 

SP and Weight(WT)

 
Q10) Draw inferences about the following boxplot & histogram

Sol:
1_For histogram


 
The most of the data points are concentrated in the range 50-100 with frequency 200.
And least range of weight is 400 somewhere around 0-10
So expected value the above distribution is 75.
Skewness: We can notice a long tail towards right so it is heavily right skewed. 

 
For Box plot: Median  is less than mean right skewed and we have outlier on the upper side of box plot and there is less data points between Q1 and bottom point.
Q11)  Suppose we want to estimate the average weight of an adult male in    Mexico. We draw a random sample of 2,000 men from a population of 3,000,000 men and weigh them. We find that the average person in our sample weighs 200 pounds, and the standard deviation of the sample is 30 pounds. Calculate 94%,98%,96% confidence interval?
¬Sol:
Using the t-distribution, it is found that:
•	The 94% confidence interval is (198.73, 201.27).
•	The 96% confidence interval is (198.61, 201.39).
•	The 98% confidence interval is (198.43, 201.57).

Q12)  Below are the scores obtained by a student in tests 
34,36,36,38,38,39,39,40,40,41,41,41,41,42,42,45,49,56
1)	Find mean, median, variance, standard deviation.
Mean= 41, Median=40, variance=24.111, standard deviation=4.910

2)	What can we say about the student marks? 
Sol: The given data is right skewed

Q13) What is the nature of skewness when mean, median of data are equal?
Sol; symmetrical
Q14) What is the nature of skewness when mean > median ?
Sol: Right Skewed
Q15) What is the nature of skewness when median > mean?
Sol: Left Skewed
Q16) What does positive kurtosis value indicates for a data ?
Sol: The data is normally distributed and kurtosis value is 0.
Q17) What does negative kurtosis value indicates for a data?
Sol: The distribution of the data has lighter tails and flatter peaks than normal distribution. 
Q18) Answer the below questions using the below boxplot visualization.
 
What can we say about the distribution of the data?
Sol: Let’s assume above box plot is about ages of the students in a school
50% of the people are above 10 years old and remaining are less
And students who’s age is above 15 are approx 40%
 
What is nature of skewness of the data?
Sol: Left skewed, median is greater than mean.

What will be the IQR of the data (approximately)? 
Sol: Approximately=8








Q19) Comment on the below Boxplot visualizations? 
 
Draw an Inference from the distribution of data for Boxplot 1 with respect Boxplot 2.
Sol:
By observing both the plots whisker’s level is high in boxplot 2 , mean and median are equal hence distribution is symmetrical.
 
Q 20) Calculate probability from the given dataset for the below cases

Data _set: Cars.csv
Calculate the probability of MPG  of Cars for the below cases.
       MPG <- Cars$MPG
a.	P(MPG>38)
b.	P(MPG<40)
c.	P (20<MPG<50)

Sol: by using filter command and installing dplyer package into ‘R’.
a.	There are 33 observations in MPG which are  greater than 38 
b.	61 observations in MPG which are less than 40
c.	71 observations are greater than 20 and less than 50

Q 21) Check whether the data follows normal distribution
a)	Check whether the MPG of Cars follows Normal Distribution 


 



b)	Check Whether the Adipose Tissue (AT) and Waist Circumference(Waist)  from wc-at data set  follows Normal Distribution 
 

       

Q 22) Calculate the Z scores of  90% confidence interval,94% confidence interval, 60% confidence interval
Sol:
Z score of 90% confidence interval is 1.65 
Z score of 94% confidence interval is 1.55 
Z score of 60% confidence interval is 0.85 

            Q 23) Calculate the t scores of 95% confidence interval, 96% confidence interval, 99% confidence interval for sample size of 25
Sol:
For 95%= 1.96
For 96%= 2.5
For 99%= 2.47

  Q 24)   A Government  company claims that an average light bulb lasts 270 days. A researcher randomly selects 18 bulbs for testing. The sampled bulbs last an average of 260 days, with a standard deviation of 90 days. If the CEO's claim were true, what is the probability that 18 randomly selected bulbs would have an average life of no more than 260 days
Sol:
t - statistics for the data is given as follows:
 
x = mean of the sample of bulbs =  260
μ = population mean = 270
s = standard deviation of the sample = 90
n = number of items in the sample = 18
 
 
 
 
t = - 0.471
For probability calculations, the number of degrees of freedom is n - 1, so here you need the t-distribution with 17 degrees of freedom.
The probability that t < - 0.471 with 17 degrees of freedom assuming the population mean is true, the t-value is less than the t-value obtained With 17 degrees of freedom and a t score of - 0.471, the probability of the bulbs lasting less than 260 days on average of 0.3218 assuming the mean life of the bulbs is 300 days.


         
