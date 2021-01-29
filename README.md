### About
The questions and datasets in this assignment were provided by the University of Michigan.  Solutions to the questions are my own.

The assignment involves finding how the population of a city correlates with the performance of said city's sports team. Performance is defined by the team's win-loss ratio, which is the number of wins over the number of wins plus the number of losses.  

This correlation analysis is carried out in questions 1 to 4, with each question focusing on one of the 4 major sports leagues in North America - NFL, NHL, NBA, MLB. 

Finally, question 5 addresses the hypothesis that given that a city has two sports teams in different sports leagues, those teams will perform the same within their respective sports league. 

### Datasets
4 datasets that each contain sports team performance within a city for the 4 sports leagues - NFL, NHL, NBA, MLB. Source: University of Michigan

1 dataset for population and sports team names within each city. Source: Wikipedia

### Summary of Results

#### Questions 1 to 4 - correlation coefficients

The correlation coefficient for all sports leagues is shown in the correlation table below.  

| | NHL | MLB | NBA | NFL |
| --- | --- | --- | --- | --- |
| **Correlation** | 0.012486 | 0.150037 | -0.176364 | 0.004282 |

In all sports leagues, the correlation coefficient is low, which indicates that there is no relation between a city's population and its team's performance.

#### Question 5 - hypothesis test

The p-value of the paired t-test is summarised below.  

| Comparison | p-value |
| --- | --- |
| NHL vs NBA | 0.022386 | 
| NHL vs MLB | 0.004545 |
| NHL vs NFL | 0.100609 |
| NBA vs MLB | 0.819462 |
| NBA vs NFL | 0.914035 |
| MLB vs NFL | 0.772811 |

If we choose a confidence level of 95%, then the p-value to accept the alternative hypothesis must be less than 5%.
This is the case for NHL vs NBA (2.2%), and NHL vs MLB (0.4%), where we must reject the null hypothesis. This means that the MLB and NBA teams perform the same as their NHL counterparts, for a given city.
