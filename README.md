# Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python

Objective:

The objective of this statistical analysis is to identify patterns and relationships among various factors that may influence a customer's likelihood of taking out a personal loan from the bank. By analyzing customer age, experience, income, family size, average spending on credit cards, education level, and other relevant variables, the bank can better understand its customer base and tailor its loan offerings accordingly.

Data Collection and Preparation:

The data for this analysis consists of a dataset containing information on customer demographics, financial characteristics, and spending behavior. Each row represents a unique customer, and the columns include attributes such as:

Customer Age: The age of the customer.
Experience: The number of years of professional experience.
Income: The annual income of the customer.
Family: The size of the customer's family.
Avg Spending on Credit Card: The average monthly spending on credit cards.
Education Level: The highest level of education attained by the customer.
Other relevant variables: Additional factors such as marital status, housing status, etc.
Before conducting the analysis, the data is cleaned and prepared to ensure accuracy and consistency. This includes handling missing values, removing outliers, and standardizing data formats.

Statistical Analysis:

Descriptive Statistics: 

Begin by calculating descriptive statistics for each variable, including measures such as mean, median, standard deviation, minimum, maximum, and quartiles. This provides a summary of the central tendency, variability, and distribution of each attribute.

Correlation Analysis: 

Perform correlation analysis to examine the relationships between pairs of variables. Determine the correlation coefficient for each pair to assess the strength and direction of the relationship. This helps identify potential predictors of personal loan uptake.

Conclusion:

Through this statistical analysis, the bank gains valuable insights into the factors that influence personal loan uptake among its customers. By understanding customer demographics, financial characteristics, and spending behavior, the bank can better tailor its marketing strategies, product offerings, and risk management practices to meet the needs of its target market and maximize loan profitability. Additionally, the insights gained from this analysis can inform strategic decision-making and help the bank maintain a competitive edge in the lending market.


Section 1

   1. A statistics test was conducted for 10 learners in a class. The mean of their score is 85 and the variance of the score is zero. What can you interpret about the score obtained by all learners?

      (Ans-1) If the variance of the scores is zero, it means that all the scores are identical and equal to the mean. In this case, all 10 learners scored 85 on the statistics test.

      It implies that there was absolutely no variability in the scores among the learners.  It could suggest that either the test was extremely easy for all learners, or there was some error or constraint in the testing process that           led to all learners achieving the exact same score.

  2. In a residential locality, the mean size of the house is 2224 square feet and the median value of the house is 1500 square feet. What can you interpret about the skewness in the distribution of house size? Are there more bigger or       smaller houses in the residential locality?

      (Ans-2) The mean and median are measures of central tendency that help describe the distribution of data. In this case:

      The mean size of the house is 2224 square feet.
      The median size of the house is 1500 square feet.
      
      When the mean is greater than the median, it suggests that the distribution is (positively skewed.)
      
      In the context of house sizes:
      
      The mean being larger than the median indicates that there are some houses with very large sizes that pull the mean upward, 
      creating a rightward skew in the distribution.
      The median being smaller suggests that there are more houses with sizes below the median value, contributing to the skewness.
      
      Therefore, the distribution of house sizes in this residential locality is positively skewed, 
      meaning there are relatively fewer larger houses compared to smaller ones.
      
      There are relatively more smaller houses compared to larger ones.

  3. ![image](https://github.com/SumitTiwari1/Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python/assets/167782156/0810af86-3888-4c46-a6bd-a4c6530b9c98)

     (Ans-3) To evaluate the variability in expenditure for both groups with respect to their mean, we should use the coefficient of variation (CV).

      The coefficient of variation is a standardized measure of dispersion that allows us to compare the variability of different 
      datasets, particularly when the means of the datasets are different. 
      It is calculated as the ratio of the standard deviation to the mean, expressed as a percentage.
      
      Here's how we would calculate the coefficient of variation for both Group 1 and Group 2:
      
      For Group 1:
      CV = (Std Dev / Mean) * 100
                  = (125000 / 500000) * 100
                  = 25%
      
      For Group 2:
      CV = (Std Dev / Mean) * 100
                  = (10000 / 40000) * 100
                  = 25%
      
      Both groups have a coefficient of variation of 25%, 
      indicating that the variability in expenditure relative to their mean is the same for both groups.
      
      By using the coefficient of variation, we can compare the relative variability of expenditure between the two groups 
      while accounting for differences in their means.

  4. ![image](https://github.com/SumitTiwari1/Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python/assets/167782156/699c0006-6117-4759-894c-5c555d76c771)

     (Ans-4)
     
       a. Which class interval has the highest frequency?
     
        the interval with the highest frequency is ("35 - 45") with 23 patients.

     b. Which age was affected the least?
     
        the interval "55 - 65" has the least number of patients, with only 5 patients. represents the age group that was affected the least

     c. How many patients aged 45 years and above were admitted?
     
        the number of patients aged 45 years and above is 14 + 5 = 19 patients.

     d. Which is the modal class interval in the above dataset
     
        The modal class interval is the interval with the highest frequency. In this case, the modal class interval is "35 - 45" with a frequency of 23 patients.

     e. What is the median class interval of age?
     
        To find the median class interval, we need to find the cumulative frequency just greater than (or equal to) half of the total frequency. Then, we look at the corresponding class interval. The total frequency is:
              
        6 + 11 + 21 + 23 + 14 + 5 = 80
              
        Half of 80 is 40. We find the cumulative frequency at or just greater than 40:
              
        Cumulative Frequency:
              
        5 - 15: 6
        15 - 25: 6 + 11 = 17
        25 - 35: 17 + 21 = 38

        So, the median class interval is (25 - 35)

5. ![image](https://github.com/SumitTiwari1/Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python/assets/167782156/18e4c0f1-7a71-4496-b43a-34160e132a58)

   (Ans-5)

To compute the average return on investment for the given data, we can use the geometric mean. The geometric mean is a measure of average that accounts for the compounding effect of returns over multiple periods, making it suitable for calculating the average return on investment over several years.


Using the data provided:

((1 + 0.36)*(1 + 0.23)*(1 - 0.48)*(1 - 0.30)*(1 + 0.15)*(1 + 0.31)^ 1/6 - 1 )

Calculating the product inside the parentheses:

(Geometric Mean) = (1.36 * 1.23 * 0.52 * 0.70 * 1.15 * 1.31)^1/6 - 1 
(Geometric Mean) = (0.3335859)^1/6 - 1
(Geometric Mean) = 1.094618 - 1 
(Geometric Mean) = 0.094618

So, the average return on investment, using the geometric mean, is approximately ( 9.46 % ) per year over the period from 2015 to 2020.

6. ![image](https://github.com/SumitTiwari1/Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python/assets/167782156/9849f387-f9f3-435a-bd11-31e0adc2d513)

   (Ans-6)

Measuring the average height of all males on Earth would be an enormous undertaking due to the sheer size of the population 
and the logistical challenges involved in obtaining accurate data from every male individual. 
However, if we were to attempt this task, we would need to employ a sampling strategy, as it is impractical to measure 
the height of every male on Earth.

Here's a potential strategy:

Sampling Methodology: 
We would need to select a representative sample of males from different regions, countries, ethnicities, 
                      ages and socioeconomic backgrounds to ensure that our sample is diverse and reflects the global 
                      male population.
                      
Regarding whether the average height would be a parameter or a statistic:

Parameter: 
The average height of all males on Earth would be considered a parameter. 
           and in this case, it represents the true average height of all males worldwide.

Statistic: 
The average height calculated from the sample data would be considered a statistic. 
           A statistic is a numerical characteristic of a sample.

In summary, measuring the average height of all males on Earth would involve sampling, data collection, and analysis, 
with the resulting average height being a parameter of the population and the calculated average height from the sample data 
being a statistic.

7. ![image](https://github.com/SumitTiwari1/Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python/assets/167782156/d1713318-1fa8-4d85-9714-8b49d7a87132)

![image](https://github.com/SumitTiwari1/Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python/assets/167782156/eaefb4e5-f02c-4e09-97b3-3ef1c500c898)


Section 2

![image](https://github.com/SumitTiwari1/Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python/assets/167782156/50504f88-1bcc-4fe4-a86a-c6b7ac237e05)

8. Give us the statistical summary for all the variables in the dataset.

![image](https://github.com/SumitTiwari1/Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python/assets/167782156/2f38b41c-4286-40c4-94f9-4e48dbf57056)

10. What statistical method will you use to examine the presence of a linear relationship between age and experience variables? Also, create a plot to illustrate this relationship.

![image](https://github.com/SumitTiwari1/Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python/assets/167782156/867c9a58-dc71-49df-af13-da297a9d0fec)

![image](https://github.com/SumitTiwari1/Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python/assets/167782156/ab319981-645e-481e-986c-548765a90f46)

11. What is the most frequent family size observed in this dataset?

    ![image](https://github.com/SumitTiwari1/Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python/assets/167782156/4d959395-bcfd-4446-b827-6f41980e478c)

12. What is the percentage of variation you can observe in the ‘Income’ variable?

    ![image](https://github.com/SumitTiwari1/Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python/assets/167782156/ea50c26e-3aaa-410a-97ef-92c37471701a)

13. The ‘Mortgage’ variable has a lot of zeroes. Impute with some business logical value that you feel fit for the data.

    ![image](https://github.com/SumitTiwari1/Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python/assets/167782156/0883435f-02e4-4297-8319-4f768163dd54)

14. Give the IQR of all the variables which are quantitative and continuous

    ![image](https://github.com/SumitTiwari1/Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python/assets/167782156/7f107d9c-9390-43d1-908f-9a05227d68ed)

15. Do the higher-income holders spend more on credit cards?

    ![image](https://github.com/SumitTiwari1/Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python/assets/167782156/726e1e0a-ec40-45aa-8a63-97fc9eed37bc)

16. How many customers use online banking? Do customers using bank internet facilities have higher incomes?

![image](https://github.com/SumitTiwari1/Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python/assets/167782156/1548ae6b-0009-4911-9ade-c9059d263fe2)

1. Using the z-score of the income variable, find out the number of observations outside the +-3σ

![image](https://github.com/SumitTiwari1/Statistical-analysis-for-the-Bank-Personal-Loan-Using-Python/assets/167782156/0c6ea829-e36e-416f-8180-87af07fd5434)










       

