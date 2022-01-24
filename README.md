# School_District_Analysis

## Overview of the school district analysis

The purpose of this project is to produce evidence for Maria that reading and math grades for Thomas High School ninth graders have been altered. In order to uphold state-testing standards, our mission is to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. We will be using Python to read in the raw data, clean it up, and perform our analysis, along with Jupyter Notebook to help us process and visulaize the data.

## Results

### District summary
    * By removing the 491 test scores from the data set, the district summary had minimal change in test scores.
    * The numbers of student remained the same as we only altered test scores, and did not remove any data points.
    
### School summary
    * The school summary should look exactly the same with the exception of THS.
    * Their rankings relative to other schools dropped considerably acorss the board.
    * Math: 93.3% (7) → 66.9% (9)
    * Reading: 97.3% (1) → 69.7% (15)
    * Overall: 90.9% (2) → 65.1% (8)