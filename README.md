# HW-Data_Structures

## Objectives

- Learn commonly used R and Python data structures.
- Gain practice using these data structures to process large datasets.
- Learn how to visualize and share the results.

## Resources

- [One Billion Row Challenge](https://1brc.dev/)
- [Python implementation using different packages to improve](https://www.linkedin.com/pulse/from-minutes-seconds-supercharging-python-billion-row-krishan-gupta-2icfe/)
- [Sorting one million](https://neopythonic.blogspot.com/2008/10/sorting-million-32-bit-integers-in-2mb.html)

## Homework

### Problem 1

Complete the following problems on leetcode. You should submit proof that your solution is correct in the form of a screenshot.

- [Number of good pairs](https://leetcode.com/problems/number-of-good-pairs/)
- [3Sum](https://leetcode.com/problems/3sum/)
- [Fill missing data](https://leetcode.com/problems/fill-missing-data/)

  
### Problem 2

- Run `python3 -m pip install -r requirements.txt` and then `python3 createMeasurements.py` to create the data. See [1brc](https://github.com/ifnesi/1brc#submitting) for additional options. Note that the data contains the city name and a temperature measurement.
- Write Python code to print out the mean and standard deviation of the temperature measurements per station, alphabetically ordered. (And try to make the processing as fast as possible)
- Write R code to print out the min, max, mean of temperature per station, alphabetically ordered.
- Measure the time of the R and python code and analyze the bottleneck.
- Create an interactive website to visualize the data. Some ideas include an R shiny interactive map displaying the location of the stations and their temperatures. See [this example](https://github.com/phillipnicol/shinyapp_demo) that was created by following [this tutorial](https://hbctraining.github.io/Training-modules/RShiny/lessons/shinylive.html). A more detailed example is [GWAS diverse monitor](https://gwasdiversitymonitor.com/). We strongly recommend using generative to AI to help design the visualization. 
