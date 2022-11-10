## Final test
1. What does the test statistic tell you?
- **It indicates how many standard errors a point estimate lies from the expected null hypothesis population value.**
- It's another word for the p-value.
- It indicates whether you should use z- or t-distribution to calculate probability.
- It indicates how far from the actual population value your sample mean lies.
<br>
2. In a group of students 25% are enrolled in physics, 23% in sociology, 17% in chemistry, 14% in political science, 12% in anthropology, and 9% in math. You are going to select an individual from the group of students. The probability of event A is equivalent to the probability that you select someone who studies social science (sociology, political science and anthropology) or physics. What is the probability of the event A’s complement?
    
>*0.25 + 0.17 + 0.09 + 0.23 + 0.14 + 0.12 = 1 -> *P(a)= 0.23 + 0.14 +0.12 + 0.25 = 0.74 -> 1 - P(a)= 1- 0.74 = **0.26***
<br>    
3. Assume your null hypothesis is μ = 6. In your sample you find a value that is lower than 6. Is it 'easier' to reject the null hypothesis with a one-tailed or two-tailed test?

- **A one-tailed test.**
- A two-tailed test.
- This depends on the level of significance.
- This depends on the P value.
<br>
4. Someone makes the following assertion: if the sample becomes larger, then the standard deviation becomes smaller. Which of the following statements is correct?

- This assertion does not apply to any distribution.
- This assertion always applies to all distributions.
- This assertion always applies to the sample distribution and the sampling distribution.
- **This assertion always applies to the sampling distribution.**
<br>
5. The largest number of Oscars received by a film in year X was 4. This was different in previous years. Below is a probability distribution for the number of Oscars per Oscar winning film. What is the standard deviation of this distribution?
    
![image](https://user-images.githubusercontent.com/58776067/196274018-345773b5-190b-45ac-a258-803e621c36d0.png)
    
>*mean = 1 * 0.56 + ….+6 * 0.02 = 1.82; sd = sqrt(0.56  * (1-1.82)^2 + … + 0.02 * (6-1.82)^2) = 1.1948* 
    

6. You draw a sample from the population of a town (n = 312) and find that of this sample, 23% are highly educated and 27% are low-educated. What is the 80% confidence interval for the proportion of highly educated people in this town?
    
>*sd = sqrt (0.23 * (1-0.23) / 312) = 0.0238, 80% IC → apha = 0.2 → p-value = 0.2/2 = 0.1 → z = - 1.28, 0.23 - 1.28 * sd < P < 0.23 + 1.28 * sd ->*  **0.20 < P <0.26**
<br>  
7. What type of table is shown below?
    
![image](https://user-images.githubusercontent.com/58776067/196275043-ae50c075-ea9c-4114-983e-3b176e600dc1.png)

- **Data matrix**
- Cross table
- Frequency table
- Scatterplot
<br>
8. You know that there is a strong correlation between the consumption of ice cream and body weight. The Pearson's r = 0.78. You also know that the average consumption of ice cream per week is five grams with a standard deviation of 1.5 grams. The average weight is 65 kg with a standard deviation of 15 kg. What is the formula of the regression line?

- ŷ = -502 + 0.078x
- ŷ = 0.078 - 502x
- **ŷ = 26 + 7.8x**
- ŷ = 7.8 + 26x  

>*b = r * sy/sx = 0.78 * (15/1.5) = 7.8; a = mean-y - b * mean-x = 65 - 5* 7.8 = 26 →* **y = 26 + 7.8x**
<br>    
9. See the sample space below. What is the probability of event B occurring, given that event A has occurred?
 
  ![image](https://user-images.githubusercontent.com/58776067/196275472-a2d1e458-6be6-43bf-8601-a91509214bfe.png)
  
 >*P(B/A) = P(A and B ) /P(A) = 0.09 / (0.17 + 0.22 +0.09) =* **0.1875**
 <br>
10. What is a probability?

- A P-value.
- An uncertainty.
- The number of times that something occurs in an experiment.
- **The proportion of times that something will occur in the long run.**
<br>
11. 25% of all students find this BS exam difficult. You select four random students. What is the probability that exactly two of them find this exam difficult?

>*P(X) = n! /x! (n-x)! * P^x * (1-P)^(n-x) → *P(x = 2) = C(2/4) * 0.25^2 * 0.75^2 = binompdf(4,0.25,2) =* **0.2109**
<br>    
12. Various forms of bias can occur when we select a sample. What is sampling bias?

- If not everyone in the population has an equal chance to enter the sampling frame.
- If not everyone in the sample actually participates in the research.
- If not everyone in the sample belongs to the population.
- **If not everyone in the sampling frame has an equal chance to get into the sample.**
<br>    
13. Variable A is normally distributed with μ = 12.30 and σ =  3.11. What is the probability that a randomly selected case will have a score of less than 14?

>*z = (14-12.30)/3.11 = 0.5466 → P-value = 0.29116 →1-0.29116 =* **0.70884**
<br>
14. A random sample of 61 Basic Statistics students were asked what they thought of statistics on a scale of 0 (very stupid) to 100 (very nice). Interestingly, students seem to find statistics quite nice: the sample mean equals 83. The sample standard deviation equals 7. We know that the standard deviation in the population (all BS students) is 8. Calculate the 90% confidence interval.

>*n = 61, mean = 83, s = 7→ se = 7/sqrt(61) = 0.896, P-value =(1-0.9)/2 = 0.05 → z = 1.645 → 83 - 1.64 * se < 90% IC < 83 + 1.645 * se → (81.53, 84.47)* 
<br>    
15. You know that for variable A μ = 1400 and σ = 300. You also know that the variable is normally distributed. You decide to change the scores of this variable
into z-scores. What is the mean and standard deviation of this new distribution?

- **Mean = 0, standard deviation = 1.**
- Mean = 1400, standard deviation = 1.
- Mean = 1400, standard deviation = 300.
- Cannot be calculated on the basis of this information.
<br>
16. Ten students reset the Basic Statistics exam. Their final grades are: 4, 4, 2, 9, 7, 9, 6, 4, 7, 8. What is the interquartile range?
    
>*excel: Q1= interquartile((4,…9), 1) = 4 , Q3 = 7.75 → Q3- Q1 =3.75*
<br>    
17. Which of the following is not the explained variance?

- The degree to which the regression equation of X and Y is better at predicting the dependent variable than the average of Y.
- **The percentage of variance in Y that is explained by the mean of X.**
- The percentage of the variance in Y which is explained with the regression equation.
- The Pearson r squared.
<br>
18. Look at the following cross table of two ordinal variables. Is there a correlation between variable A and B?

![image](https://user-images.githubusercontent.com/58776067/196278067-c48fedd1-0eea-498d-947a-dd447918f03b.png)
    
- Cannot be seen from the table.
- Yes, there is a negative correlation.
- **No, there is no correlation.**
- Yes, there is a positive correlation.
<br>
19. Look at the table below. Calculate the Pearson's r.
    
![image](https://user-images.githubusercontent.com/58776067/196277658-9e801089-81c3-4149-a1f5-ea1d947e77de.png)
   
>*CORREL(A29:A31,B29:B31) = 0.91*
    
<br>
20.  Based on a random sample of n = 2345, the 95% confidence interval of variable X is (7.25, 9.12). You expect that the mean in the population is different from 7 at α = 0.05. What can you conclude?

- Nothing, because you have not enough data to determine that.
- **The value in the population is indeed different from 7.**
- You cannot reject the null hypothesis.
- This confidence interval is wrong.
<br>
21. Which of the following statements about the regression line is not correct?

- The constant indicates the place where the regression line crosses the Y-axis.
- **The regression line is the line of which the sum of the residuals is the smallest.**
- The regression line can run horizontally.
- The regression coefficient is the change in the Y value with 1 unit increase in the X value.
<br>    
22. You’re going to draw a random sample of professional football players because you want to know what percentage have completed high school. You want to have a margin of error of up to 0.03 at a confidence level of 90%. How big should your sample be?

- Minimum 1068
- **Minimum 748**
- At least 30
- Minimum 456   
 
>*n = 1.645^2 * 0.25/0.03^2 =751 ( P-value = 0.9 → z-score = 1.645)*   
<br>
23. 81 random elementary schools were asked for their average exam scores (sample mean = 535, sample standard deviation = 7). Calculate the 98% confidence interval.
    
- (533.41, 536.59)
- **(533.15, 536.85)**
- Not possible to calculate based on this information.
- (528.00, 542.00)

>*n = 81, mean = 535, s = 7→ se = 7/sqrt(81) = 0.777, P-value =(1-0.98)/2 = 0.01 → z = 2.30 → 535 - 2.3 * se < 98% IC < 535 + 2.3 * se →* **(533.20, 536.80)** 
<br>
24. A type I error means that:

- The null hypothesis is true, and you do not reject the null hypothesis.
- **The null hypothesis is true, and you reject the null hypothesis.**
- The null hypothesis is false, and you reject the null hypothesis.
- The null hypothesis is false and cannot reject the null hypothesis.
<br>Y    
25. You know that the heights of four people are: 156 cm, 184 cm, 172 cm and 165 cm. What is the standard deviation?
    
>*STDEV.S(A38:D38) =* **11.81**   
<br>
26. Last year the mean turnover of a group of companies was 434,000 euro. You have good reasons to expect that this year’s turnover will be higher. Your null hypothesis is therefore: μ = 434,000. Your alternative hypothesis is: μ > 434,000. You randomly sample 101 companies from the population. The sample mean turns out to be 450,000 euro, with a standard deviation of 100,000 euro. Calculate the test statistic. Which of the following statements is correct?
        
- You do not reject the null hypothesis at α = 0.05, and not at α = 0.10.
- You reject the null hypothesis at both α = 0.05 and α = 0.10.
- You reject the null hypothesis at α = 0.05, but not at α = 0.10.
- **You reject the null hypothesis at α = 0.10, but not at α = 0.05.**

>*z = (450,000 -434,000)/(100,000/sqrt(101) = 1.60, alph = 0.05 → z-score = 1.66 not rejected , apha = 0.1 → z-score = 1.28  rejected*
<br>
27 Film critics gave the film Basic Statistics: The Movie an average rating of 8.1 (on a scale of 0-10). The standard deviation is 0.7. You drew a random sample of n = 56 from all film critics and asked them to rate the film Basic Statistics: The Movie with a number. What is the probability that the average rating in the sample is greater than 8.0?
    
>*z = (8 -8.1)/(0.7/SQRT(56)) = -1.069 → P-value = 14.457 → 1-14.457 =* **86%**   
<br>
28. You draw a sample from the population of Dutch voters. You do this by randomly selecting 10 voters from each municipality. What kind of sample is this?

- Cluster random
- **Stratified random**
- Snowball
- Convenience
<br>
29. What does the 95% confidence interval tell us?

- **In 95% of cases when we sample from a population, the population mean falls within the interval: sample mean ± 1.96 * standard deviation of the sampling distribution.**
- In 95% of cases when we sample from a population, the sample mean falls within the interval: sample mean ± 1.64 * standard deviation of the sampling distribution.
- In 95% of cases when we sample from a population, the population mean falls within the interval: sample mean ± 1.64 * standard deviation of the sampling distribution.
- In 95% of cases when we sample from a population, the sample mean falls within the interval: sample mean ± 1.96 * standard deviation of the sampling distribution.
<br>    
30. What is a characteristic of the t-distribution?

- **A t-value that is multiplied with a standard error is equal to the margin of error for a confidence interval of a mean.**
- The t-distribution has the same shape as the normal distribution.
- The t distribution has a mean of one.
- The t-distribution approaches the normal distribution if it has a large standard deviation.  
