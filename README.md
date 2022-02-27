# Stock Analysis

## Overview of Project
The purpose of this project was to analyze Steve's data set with a refactored code, therefore increasing efficiency while still giving us the same results we're looking for. Right now we have 12 stocks - however, once 12 turns into thousands, it would take a much larger amount of time to perform the analysis if I didn't edit the code.

## Results

Before refactoring the code, it was looping through all of the data 12 times. Now that I improved the logic of the code, it only looped through the data once while still collecting all of the information it needed to collect.

Taking a look at the the screenshots below, you can see that before refactoring the code, it ran in 0.27 seconds. After refactoring the code, it ran in .06 seconds - making it run 4.5 times faster than before! Even though it didn't make much of a difference in this case, it would save you a lot more time with a much larger data set.

### Original Code Run Time

![Screen Shot 2022-02-26 at 3 55 49 PM](https://user-images.githubusercontent.com/96892095/155865549-68d0fe08-9cfa-42da-8404-62eea732cf1f.png)![Screen Shot 2022-02-26 at 3 55 26 PM](https://user-images.githubusercontent.com/96892095/155865552-565b5b9c-a8ec-4384-8012-7cf678d3c1b1.png)



### Refactored Code Run Time

![VBA_Challenge_2017](https://user-images.githubusercontent.com/96892095/155865534-eeb7d20f-e8dd-4548-9d47-7225849a2cbd.png)![VBA_Challenge_2018](https://user-images.githubusercontent.com/96892095/155865536-4a47ae58-d32d-4074-9562-cec915dd70e2.png)


## Summary

### 1. What are the advantages or disadvantages of refactoring code?

The advantage of refactoring code is the amount of time you save when you run it. It takes fewer steps and uses less memory. However, the disadvantage of refactoring code is that it can be time consuming.

### 2. How do these pros and cons apply to refactoring the original VBA script?

When I worked on the original code, understood what it did, and got it to run successfully, it was much easier to take a step back and think about how I could improve it. It was not absolutely necessary to refactor the code, and it would be time consuming to do it - but once I did, it ran much faster and made the process much more efficient. Therefore, it was worth it in the long run.
