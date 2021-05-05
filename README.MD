# Stock Analysis for Steve

## Project Overview

This VBA script was written for Steve who needed to provide insight into stock performance for his parents. As first time investors, Steve's parents were interested in the performance of the DQ stock. Upon analyzing the results of the DQ stock performance, Steve decided he wanted to perform the analysis for all stocks within the data set to advise his parents of other potential stocks to invest in. The VBA script was refactored to include variables that would analyze the performance of all stocks in the data set provided and produce a formatted summary.

## Results: Using images and examples of your code, compare the 
### Stock performance Comparison
Overall, the stocks had a better performance in 2017 than they did in 2018. In 2017 the only stock that did not have a positive return was TERP, while in 2018 only NEPH and RUN had positive returns. Unfortunately for Steve's parents, DQ had an excellent performance in 2017 with a 199.4% return, but underperformed in 2018 with a -62.6% return.

### Execution time Comparison
 By refactoring the code, I was able to significantly improve the performance of the code. As you can see in the images below, the execution time of the original code was 0.6796875 seconds, and it was optimized to 0.1484375 seconds for 2017 and 2018.
 
<img width="292" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/17945476/117085593-38481300-ad18-11eb-9541-088b796a0917.png">
<img width="285" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/17945476/117085609-41d17b00-ad18-11eb-94af-bb62ffa48dc8.png">


## Summary
### What are the advantages or disadvantages of refactoring code?

One of the advantages of refactoring code is that the code can be optimized for performance or reused to achieve a similar end-goal as the original code.
One of the disadvantages of refactoring code is that if it is not properly commented or structured, you may spend more time trying to figure out what the code is doing than it would take to write a new program. You may also be refactoring old code which you may have forgotten the structure of.


### How do these pros and cons apply to refactoring the original VBA script?

The above-mentioned advantage of refactoring code applies to the original VBA script because the Green Stocks code was refactored to optimize the execution time of the code, as well as incorporating variables to remove hard-coded values, which also improved the quality of the code.

The disadvantage mentioned doe snot apply to the refactored VBA script as I was refactoring code that was recently written and I knew what the purpose of each section was. 