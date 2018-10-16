# CitiBike Review
Andrea Hassler (ah4412)  

## a. Verify that their null and alternative hypotheses are formulated correctly.
### Verification:
There do not appear to be an idea and hypotheses set up.  
### Suggestions: 
Based on the data selected, an idea might be to examine if younger riders take more trips on weekends. Next, we would need a set of testable hypotheses and an alpha level.  

**NULL:** For weekend trips, the proportion of trips taken by riders born after 1990 is the same or smaller than the proportion of trips taken by riders born in or before 1990.  
$p_{younger} \leq p_{older}$

**ALT:** For weekend trips, the proportion of trips taken by riders born after 1990 is greater than the proportion of trips taken by riders born in or before 1990.  
$p_{younger} > p_{older}$

**Alpha level:** 0.05

## b. Verify that the data supports the project: i.e. if the data has the appropriate features (variables) to answer the question, and if the data was properly pre-processed to extract the needed values (there is some flexibility here since the test was not chosen yet).

The data mostly supports the project. Gender and tripduration would be extraneous here (perhaps this was part of the author's original idea?). The only variables needed are starttime and birthyear. It looks like birthyear was correctly transformed to an indicator variable of 0 for born in/before 1990 and 1 for born after 1990. The first plot is a nice visualization of the data.



