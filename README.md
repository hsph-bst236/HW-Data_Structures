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

Complete the following problems on leetcode. You should follow the general [homework submission guidelines](https://junwei-lu.github.io/bst236/chapter_syllabus/syllabus/#homework-submission-guidelines) to add you code and ReadMe.md in the homework repository. You should also add in ReadMe.md the proof that your solution is correct in the form of a screenshot of the leetcode.

- [Number of good pairs](https://leetcode.com/problems/number-of-good-pairs/)
- [3Sum](https://leetcode.com/problems/3sum/)
- [Fill missing data](https://leetcode.com/problems/fill-missing-data/)

  
### Problem 2

- Run `python3 -m pip install -r requirements.txt` and then `python3 createMeasurements.py` to create the data. See [1brc](https://github.com/ifnesi/1brc#submitting) for additional arguments (that can be used for debugging). Note that the data contains the city name and a temperature measurement.
- Write a python script called `station_quantiles.py` that computes (and prints) the 25th, 50th, and 75th percentiles of temperature measurements per station, alphabetically ordered. 
- Write R script `station_mean_max.R` to print out the min, max, mean of temperature per station, alphabetically ordered. Run your code on the class cluster using one CPU node and report the running time. (Tip: Use AI to improve the running time comparable to python with prompts like: translate python to R, using similar R packages like polars or DuckDB, other ways to optimize the running. See how AI may help you to optimize the code).
- Run your code on the class cluster using one CPU node. Measure  and report the time of the R and python code and analyze the bottleneck. Though not required, we encourage you to try different approaches and report how the running time is improved.
- Create an interactive website to visualize the data and deploy it using Github. You can decide what to visualize. Briefly demonstrate how to use the website in ReadMe. (Tip: Ask AI how to deploy the website on Github. Some ideas include an R shiny interactive map displaying the location of the stations and their temperatures. See [this example](https://github.com/phillipnicol/shinyapp_demo) that was created by following [this tutorial](https://hbctraining.github.io/Training-modules/RShiny/lessons/shinylive.html). One motivating demo example is [GWAS diverse monitor](https://gwasdiversitymonitor.com/). We strongly recommend using generative AI to help design the visualization. )
