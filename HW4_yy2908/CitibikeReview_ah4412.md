# CitiBike Review
Andrea Hassler (ah4412)  

## a. Verify that their null and alternative hypotheses are formulated correctly.
### Verification:
There do not appear to be an idea and hypotheses set up.  
### Suggestions: 
Based on the data selected, an idea might be to examine if younger riders take more trips on weekends. Next, we would need a set of testable hypotheses and an alpha level.  

**NULL:** The proportion of weekend trips taken by riders born after 1990 is the same or smaller than the proportion of weekend trips taken by riders born in or before 1990.  
_H0: proportion(younger) - proportion(older) <= 0_

**ALT:** The proportion of weekend trips taken by riders born after 1990 is greater than the proportion of weekend trips taken by riders born in or before 1990.  
_HA: proportion(younger) - proportion(older) > 0_

**Alpha level:** 0.05

## b. Verify that the data supports the project: i.e. if the data has the appropriate features (variables) to answer the question, and if the data was properly pre-processed to extract the needed values (there is some flexibility here since the test was not chosen yet).

The data mostly supports the project. Gender and tripduration would be extraneous here (perhaps this was part of the author's original idea?). The only variables needed are starttime and birthyear. It looks like birthyear was correctly transformed to an indicator variable ('>1990') of 0 for born in/before 1990 and 1 for born after 1990. The first plot is a nice visualization of the data, though it could be improved by using fraction instead of count. The next step would be calculating the proportion of trips taken on weekends for younger and for older riders. 

## c. Choose an appropriate test to test H0 given the type of data, and the question asked. You can refer to the flowchart of statistical tests for this in the slides or Statistics in a Nutshell.  

An appropriate test would be the z test of difference of two proportions. This test requires that we assume normality.





