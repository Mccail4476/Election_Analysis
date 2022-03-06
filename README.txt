# Election_Analysis prior to the Challenge
Using Python to determine Election results.

## Project Overview
The goal of this project is to determine who is the winner in a Colorado Election with a provided raw datasheet of votes. The employers, Seth & Tom, help guide on steps needed in order to tabulate the winning candidate in a step-by-step method. First step of this process is to count how many number votes are there in the voting data sheet. Next is to get the names of the candidates that appear on the data sheet. Following up on that is to calculate how many votes each candidate received. Afterward, we tabulate the percentage that each candidate has recieved based off of the previous steps. We then determine the winner based on the candidate with the highest votes & percentage. Lastly, we have the results printed on another Python file to have the results saved so they can be sent out for review.

# Resources
The project was completed using Visual Studio Code version 1.64.2 (user setup) & Python 3.7.6.

# Challenges
The hardest part of this overall project is to implement a new language that was just taught and apply it to a real world scenario. Despite Seth & Tom walking every step of the way, it was still complicated to make sense of why certain code lines work. Furthermore, I will still receive errors on the execution of the script for different reasons (indentation error, spelling error, etc.). These obstacles forced the idea to learn why the code was working. This is crucial in order to think like a programmer/coder. Through more practice using concepts taught in Module 3, one can become more proficient in Python. As the old saying goes, practice makes habit.

## Summary
After performing the full script thanks to Seth & Tom, we can see from final results that out of the three candidates, Diana DeGette won by 73.8% of total votes. Following up on the winner is Charles Casper Stockham at 23.0% & Raymon Anthony Doane at 3.1%. Using Python and the full script, we were able to process 369,711 votes in a matter of seconds & have it printed on a different file in a clean and concise manner. A key take-away is that if one is using the proper code, automation can save a lot of time & cost of labor without error. Since Python is not unique to only counting election votes, we can apply Python to other data analysis thanks to how versatile its coding langauge is.  



# Written Analysis of the Election Audit (Challenge)

## Overview 
The purpose of this election audit analysis is to gather statistic analysis of the candidates & counties involved for the Colorado election. Using Python to gather raw data from one .CSV file & outputting onto a text file, Seth & Tom will be able to see the following:
1. How many votes each candidate recieved.
2. How many votes came from which county.
3. The winning candidate with the highest vote.
4. The county that provided the highest voting turnout.


## Election-Audit Results 
![Electon_analysis_txt_file](https://user-images.githubusercontent.com/99565016/156943542-2f5cca8e-158c-4611-bdf0-00a16a10f8e2.png)

***figure 1: The final results displayed after running the updated Python code***

### Highlight of the results

1. How many votes were cast in this congressional election?   
369,711 votes total

2. Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

![county_results](https://user-images.githubusercontent.com/99565016/156943896-91e48b21-9b61-4748-98ab-e4f37bd66c79.png)

***figure 2: using the above code, we can calculate from the election results tab the number of votes and percentage of total votes for each county***

Jefferson: 10.5% (38,855 votes), Denver: 82.8% (306.055 votes), Arapahoe: 6.7% (24,801 votes)

3.Which county had the largest number of votes? 

Denver had the largest votes by county. We use the code that's displayed at the bottom of figure 2 to tabulate the largest county turnout.

4.Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

![candidate_results](https://user-images.githubusercontent.com/99565016/156944018-f01f29ee-67ce-4b0b-b313-5df629112f0d.png)

***figure 3: using the above code, we can find out the number of votes and percentage of total votes for each candidate***

Charles Casper Stockham: 23.0% (85.213 votes), Diana DeGette: 73.8% (272,892 votes), Raymon Anthony Doane: 3.1% (11,606 votes)

5. Which candidate won the election ,what was their vote count, and what was their percentage of the total votes?

Diana DeGette won with 272,892 votes, which is 73.8% of the total votes. Refer to the bottom of figure 3 to see how the winning candidate was determined from the Python code.


## Election-Audit Summary

### Summary
The Python code generated from this module is used to determine a winning candidate and highest turnout by county using votes & percentages. This script isn't limited to the Colorado election though. At the hands of a proficient Python coder, this script can be modified easily to match any other election results, as long as there is little to no deviations in the format of the raw data. Take for example the Election comission committee wanted to the same results of next year's election with new candidates. A simple re-run of the script on the new election results.csv will quickly generate the winning candidate & highest county by votes. Another example the committee wanted to find out the winning candidate & which county give the highest votes of a different state, such as an Arizona election. The script can quickly generate the winning candidate & county of highest votes in a matter of seconds. Python code is very versatile & can be used in a number of situations.
