# Stock Analysis Project

## Overview


The purpose of this project was to build an automated analytical tool in VBA that could evaluate specific stock performance in regards to trading volume and percent return over a calendar year period. The intital code that was introduced in the module was then compared with refactored code to determine if the refactored code provided benefits in terms of run speed and coding simplicity.

## Results

The results of the project indicated stock returns for 2017 generally outpaced 2018 returns for the specific set of stocks analyzed. Of the 12 stocks for whom the yearly performance was evaluated, only one stock (TERP) managed a negative return in each yearly period for which the analysis was performed. Two stocks (ENPH and RUN) managed positive returns for both 2017 and 2018. In regards to our analytical tool, the refactored code greatly outperformed the original code in terms of run speed. When comparing run sppeds of the two versions of code, the refactored code for both years had an average run speed of 0.18 seconds vs. an average run spped of 0.94 seconds for the original code.

Original script run speeds are below for 2018 and 2017, respectively.

![2018 performance_original](https://user-images.githubusercontent.com/86081274/125226300-d28b8080-e29e-11eb-9843-a3e8c2b6d975.PNG)

![2017 performance_original](https://user-images.githubusercontent.com/86081274/125226456-21391a80-e29f-11eb-9066-dc8d1b8e4efc.PNG)


Improved run speeds were seen with the refactored code as shown below:

![2018 performance_refactored](https://user-images.githubusercontent.com/86081274/125226795-be944e80-e29f-11eb-889a-bcfae72f9b8e.PNG)

![2017 performance_refactored](https://user-images.githubusercontent.com/86081274/125226816-c6ec8980-e29f-11eb-94ff-50ed164c1d12.PNG)


## Summary


There are a number of potential advantages and disadvantages associated with refactoring code. Some of the advantages of refactoring can include simplification of the code via the elimination of overly repetitive code, improving the readibility of the code to others, and improved performance of the code. Disadvantages of refactoring may include the introduction of unwanted errors and the unknown benefits vs. time required to refactor code. In terms of our project, refactoring the code greatly improved the run spped of the script and the use of indexed arrays allowed for more concise code structure overall.
